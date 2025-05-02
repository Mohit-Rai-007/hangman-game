# 🎮 Hangman Game in Python

This is a terminal-based implementation of the classic Hangman word guessing game built using Python.

## 🧠 How It Works

- A random word is selected from a list.
- The player has **6 lives** to guess the word, one letter at a time.
- Each incorrect guess reduces a life.
- The game ends when:
  - The word is guessed correctly (**you win** 🎉), or
  - All lives are lost (**you lose** 💀)

Visual stages of the Hangman are displayed as you play.

## 📁 Project Structure

├── hangman.py # Main game logic
├── hangman_words.py # Contains the word list
├── hangman_art.py # Contains ASCII art for logo and hangman stages
├── README.md # Project documentation (this file)


## 🛠 Requirements

- Python 3.x

No external libraries are needed—everything uses built-in Python modules like `random`.

## ▶️ How to Run

1. Clone this repository or download the files.
2. Make sure all three files (`hangman.py`, `hangman_words.py`, `hangman_art.py`) are in the same directory.
3. Open your terminal in that directory.
4. Run the game

📌 Features
Clean terminal UI

ASCII art hangman stages

Tracks guessed letters

Input validation for repeated guesses

Easy to extend (you can add more words to hangman_words.py)

🧠 What I Learned
Basics of Python control flow and loops

String manipulation

Working with multiple files and modular code

Using lists, functions, and conditionals

Git and GitHub for version control and collaboration

💡 Future Improvements
Add difficulty levels (easy/medium/hard)

Use a larger word list from a file or API

Add GUI using Tkinter or web version using Flask

👨‍💻 Author
Made with ❤️ by Mohit Rai :)