
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game using Python. In this assignment, you will practice loops, conditionals, string manipulation, and user input while managing game state.

## 📝 Tasks

### 🛠️	Build the Core Hangman Mechanics

#### Description
Create the main game logic for Hangman, including word selection, guess handling, and progress display.

#### Requirements
Completed program should:

- Randomly choose one word from a predefined list of words.
- Ask the player to guess one letter at a time using `input()`.
- Show the current word progress after each guess using placeholders such as `_ _ _ _`.
- Reveal all matching letter positions when the guess is correct.

### 🛠️	Handle Game Outcomes and Feedback

#### Description
Finish the game flow by tracking incorrect guesses, stopping at win/lose conditions, and displaying clear feedback to the player.

#### Requirements
Completed program should:

- Track how many incorrect guesses remain and update this value after wrong guesses.
- End the game with a win message when the player guesses the full word.
- End the game with a lose message when attempts run out, and show the correct word.
- Display helpful status messages after each guess so the player understands what happened.
