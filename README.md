Hangman Game

A classic word-guessing game built with Tkinter.

Gameplay

- Start a new game by clicking the "Start Game" button.
- Guess a letter by typing it in and clicking "Submit Guess".
- The game will display the Hangman stage, wrong guesses count, and the word with guessed letters revealed.
- Win or lose conditions will be displayed accordingly.

Features

- Random Word Selection: A random word is chosen from a predefined dictionary for each new game.
- ASCII Art Hangman: The game displays an ASCII art representation of the Hangman stages, updating with each wrong guess.
- Wrong Guesses Tracking: The game keeps track of wrong guesses and displays the count.
- Win/Lose Conditions: The game displays a winning message when the word is fully guessed, and a losing message when the maximum number of wrong guesses is reached.
- Start New Game: The game can be restarted by clicking the "Start Game" button again.

Technical Details

- Built with Tkinter: The game uses Tkinter for the graphical user interface (GUI).
- Python 3.x compatible: The game is written in Python 3.x and is compatible with Python 3.x versions.
- Predefined Word Dictionary: The game uses a predefined dictionary of words, which can be easily expanded or modified.

Code Highlights

- print_hangman(): A function that prints the ASCII art for the current Hangman stage.
- print_word(): A function that prints the word with guessed letters revealed.
- guess_letter(): A function that handles the letter guessing logic.
- start_game(): A function that initializes the game and sets up the GUI.
