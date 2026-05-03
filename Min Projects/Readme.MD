# 🐍 Python Mini Projects

A collection of beginner-friendly Python mini projects covering games, utilities, and tools — all built using core Python concepts.

---

## 📁 Projects Overview

| # | Project | Description |
|---|---------|-------------|
| 1 | 🪨 Rock Paper Scissors | 3-round game vs computer with score tracking |
| 2 | 🔑 Random Password Generator (Custom) | Build passwords with custom mix of letters, numbers & symbols |
| 3 | 🪝 Hangman Game | Classic word-guessing game with 6 lives |
| 4 | ❤️ Love Calculator | Fun score calculator based on letter frequency |
| 5 | 🔐 Caesar Cipher | Encrypt and decrypt messages using character shifting |
| 6 | 🔢 Number Guessing Game | Guess a number with higher/lower hints |
| 7 | 📝 Multiple Choice Quiz | Interactive quiz with scoring |
| 8 | ✅ To-Do List | Basic CLI task manager (add, view, remove tasks) |
| 9 | 🎲 Dice Roller | Roll a dice repeatedly until you stop |
| 10 | 🔑 Random Password Generator (Quick) | One-line 20-character password generator |
| 11 | ⏰ Alarm Clock | Time-based alarm using `winsound` (Windows) |
| 12 | 📂 File Organizer | Auto-sorts files in a folder by their extension |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Standard libraries: `random`, `string`, `os`, `shutil`, `time`
- `winsound` (built-in on Windows — used only for the Alarm Clock)

### Run any project
Clone the repo and open the notebook:
```bash
git clone https://github.com/your-username/python-mini-projects.git
cd python-mini-projects
jupyter notebook projects.ipynb
```

Or copy any individual cell into a `.py` file and run it directly:
```bash
python project_name.py
```

---

## 📌 Project Details

### 🪨 Rock Paper Scissors
Play 3 rounds against the computer. Tracks scores each round and announces the final winner.

### 🔑 Random Password Generator (Custom)
You control how many lowercase letters, uppercase letters, numbers, and special characters go into your password. The result is shuffled for randomness.

### 🪝 Hangman
A random word is chosen and you guess one letter at a time. You lose after 6 wrong guesses.

### ❤️ Love Calculator
Counts letters from "TRUE" and "LOVE" across two names and combines the totals into a love score — just for fun!

### 🔐 Caesar Cipher (Encryption & Decryption)
Encrypts a message by shifting each character a set number of positions in the alphabet, then decrypts it back.

### 🔢 Number Guessing Game
You pick a secret number (1–100) and the computer tries to guess it, guided by your higher/lower hints. Tracks the number of attempts.

### 📝 Multiple Choice Quiz
A 3-question quiz on general knowledge. Displays options, accepts A/B/C/D input, and shows the final score.

### ✅ To-Do List
A simple CLI task manager with a menu to add, view, and remove tasks.

### 🎲 Dice Roller
Rolls a 6-sided dice and lets you keep rolling until you enter `N`.

### 🔑 Quick Password Generator
Generates a strong 20-character password from letters, digits, and punctuation in one line.

### ⏰ Alarm Clock
Checks the current system time in a loop and beeps when the set time is reached. *(Windows only — uses `winsound`)*

### 📂 File Organizer
Scans a folder, creates subfolders named after each file extension, and moves files into their respective folders automatically.

---

## 🛠️ Concepts Covered

- `random` module — choices, shuffling, randint
- `string` module — ascii letters, digits, punctuation
- Loops, conditionals, and functions
- File system operations with `os` and `shutil`
- String manipulation and indexing
- Basic CLI user input handling

---

## 🤝 Contributing

Feel free to fork this repo, improve any project, or add your own mini project via a pull request!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
