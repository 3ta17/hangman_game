# Hangman Game

A Python implementation of the classic word-guessing game "Hangman." The player attempts to guess a randomly selected word one letter at a time, while trying to avoid losing all their lives.

---

## Features

- **Random Word Selection**: Words are selected randomly from a predefined list.
- **Interactive Gameplay**: Users can input guesses, and the program provides real-time feedback.
- **Dynamic Hangman Visuals**: The game includes ASCII art that changes as the player loses lives.
- **Word List**: Includes a comprehensive list of challenging words to guess.

---

## Files

1. **`hangman.py`**:
   - Main script to run the Hangman game.
   - Manages the game loop, user input, and overall logic.

2. **`hangman_art.py`**:
   - Contains ASCII art for the hangman stages and the game logo.

3. **`hangman_wors.py`**:
   - Contains a list of words used in the game.

---

## How to Play

1. Run the `hangman.py` script.
2. The game will display a placeholder for the word to guess (e.g., `_____`).
3. Enter one letter at a time as your guess.
4. If the guessed letter is correct, it will replace the placeholder(s) in the word.
5. If the guessed letter is incorrect, you lose a life and progress one step closer to "hanging."
6. The game ends when:
   - The player correctly guesses the entire word (Win).
   - The player runs out of lives (Lose).

---

## Requirements

- **Python**: 3.6 or higher.
