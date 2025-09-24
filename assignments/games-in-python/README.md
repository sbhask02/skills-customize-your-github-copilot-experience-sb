

# 🎮 Hangman Game Challenge

## 🎯 Objective
Build a classic Hangman game in Python. Practice string manipulation, loops, conditionals, and random selection while creating an interactive word-guessing experience.

## 📝 Tasks

### Task 1: Set Up Word List
**Description:** Create a list of words for the game to choose from randomly.
**Requirements:**
- Define a Python list containing at least 10 words
- Use `random.choice()` to select a word for each game

### Task 2: Game Loop & User Input
**Description:** Implement the main game loop that accepts letter guesses and updates the display.
**Requirements:**
- Prompt the user to guess a letter
- Show current progress (e.g., `_ a _ _ m a n`)
- Track and display incorrect guesses remaining
- Prevent repeated guesses

### Task 3: Win/Lose Logic
**Description:** End the game when the word is guessed or attempts run out, and display appropriate messages.
**Requirements:**
- Detect win (all letters guessed) and lose (no attempts left)
- Print a congratulatory or encouragement message

### Example
```python
Word: hangman
Guess: a
Progress: _ a _ _ m a n
Incorrect guesses left: 5
```
