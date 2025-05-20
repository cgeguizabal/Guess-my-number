# 🎯 Guess the Number Game

This is a simple **JavaScript-based number guessing game** that helps reinforce key DOM manipulation skills and event handling concepts. The player must guess a randomly generated number between 1 and 20. Feedback is given through dynamic UI changes and messages.

## 🚀 Features

- Random number generation between 1 and 20
- Input validation and feedback messages
- Score tracking and highscore system
- Dynamic UI changes when winning or losing
- "Play Again" functionality to reset the game

## 🧠 Concepts Practiced

This project helped me practice and understand:

- DOM manipulation with `document.querySelector()`
- Handling user input with `addEventListener()`
- Updating styles dynamically via JavaScript
- Using functions for cleaner, reusable code (like `displayMessage()`)
- Conditional logic and control flow
- Using state variables (`score`, `highscore`, and `secretNumber`)
- Refactoring repetitive code

## 📁 Files

- `index.html`: Basic HTML structure with elements like input fields, buttons, and message containers
- `style.css`: Styling for the game interface (not included in this snippet)
- `script.js`: Main game logic written in JavaScript (the file above)

## 🕹️ How to Play

1. Enter a number between 1 and 20.
2. Click the **Check** button.
3. You'll get feedback like:
   - 🎉 Correct Number
   - ☝️ Too High!
   - 👇 Too Low!
   - ⛔ No Number!
4. You win if your guess matches the secret number.
5. Click **Again** to reset the game and try again!
