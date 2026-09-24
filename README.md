# Specialisterne-Projekter

## Week 1 - Calculator
Link: [Calculator](https://github.com/RasmusHS/Calculator-Specialisterne) <br>
Optional project for week 1. Week 1 was mainly for introductions and setup, so this project was for if you had some time to kill. <br>
Unlike the usual calculators many of us have made before with hardcoded amount of numbers, I decided to make one that takes a mathematical expression of any length and gives you the result. <br><br>
Requirements: 
- Have to support: plus, minus, multiplication, divition, exponents, square root, and parentheses.

The way we humans write math expressions is called the infix notation, but computers struggle with that one, so we have to convert an expression into postfix notation, which is much easier for computers to use. <br>
Another challenge was telling a function apart, sqrt(), from a set of parentheses, but I managed to get it working in the end, with the added benefit of being able extend the application with other functions like sin() and cos(). <br>

## Week 2-3 - Blackjack
Link: [Blackjack](https://github.com/RasmusHS/Blackjack) <br>
Mandatory project. <br>
Pretty open project where we had to make the game blackjack. The challenge here came down to scope: What architecture? what ui? which rules to implement? <br><br>
Requirements:
- Test coverage of 95%

I ended up going with a simple layered architecture comprising of: presentation and core. <br>
For the presentation layer I made a CLI as the interface. <br>
In the Core I took a few steps to allow for more players in the future by, for example, having the game load a list of players rather than a single player object. <br><br>
I deemed persistence and database layers unnecessary. The game does not need to persist data long term to function and would only serve to store game scores or to resume games. <br> 
Game scores could be used for statistics, which would be interesting for a larger project with more time. Meanwhile, the ability to stop and then resume a game later, would require more systems like user creation and login.
