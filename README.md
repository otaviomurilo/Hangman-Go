# Hangman Game 🎮

A simple implementation of the classic Hangman game in Go.

## How to Play?
- The game randomly selects a word from a file (`words.txt`).
- The player has to guess the word one letter at a time.
- For each incorrect guess, the number of attempts decreases.
- The game ends when the player guesses the word correctly or runs out of attempts.

## Features
- **Random Word Selection**: The game picks a word from a file (`words.txt`) to challenge the player.
- **Guess Tracking**: The player can guess letters, and previously guessed letters are tracked to avoid repetition.
- **Hangman Display**: The number of incorrect attempts is visually represented by a hangman figure.
- **Word State Display**: The current word state is displayed, showing guessed letters and underscores for unguessed letters.
- **Attempts Counter**: The player has a limited number of attempts (6) to guess the word.

## Technologies Used
- **Go (Golang)**: The core programming language used to build the game.
- **Standard Library**: The game makes use of Go’s built-in packages like `fmt`, `os`, `strings`, `bufio`, and `math/rand`.

## How to Run?


1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hangman-go.git
   cd hangman-go
   go run main.go
