# codealpha_task1
Developed hangman project using python for codealpha internship
Hangman Game in Python
Overview
This is a Python implementation of the classic Hangman game. The game randomly selects a word from a predefined list of words, and the player has to guess the word by suggesting letters within a certain number of attempts. The game will display a series of blanks for the letters of the word and gradually reveal the correct letters as the player guesses them. Incorrect guesses decrease the number of remaining attempts. The game ends when the player guesses the word correctly or runs out of attempts.

Features
Random word selection from a list.
Tracks the number of incorrect guesses.
Displays the word as blanks and fills in correct guesses.
Shows a "hangman" graphic with each wrong guess (optional, depends on implementation).
Supports letter guesses and checks for repeated guesses.
Keeps the player informed about the number of remaining attempts and guessed letters.
End of game messages for both win and loss scenarios.
Requirements
Python 3.x or above
Installation
Clone or download the repository to your local machine.

Open a terminal (or command prompt) and navigate to the project folder.

Run the game by executing the following command:

bash
Copy
python hangman.py
How to Play
After starting the game, the program will display blanks representing the letters of the word.
The player will be prompted to input a letter.
If the letter is in the word, it will be revealed in the blanks.
If the letter is not in the word, the player loses one attempt.
The game continues until the player either guesses all the letters in the word or runs out of attempts.
