# kb-task-2
Number Guessing Game (Python CLI Project)
Project Overview
This is a beginner-level Python CLI project where the user tries to guess a randomly generated number between 1 and 100. The game provides hints ("Too high" or "Too low") and counts the number of attempts made until the correct guess.

The project’s purpose is to practice Python basics including loops, conditionals, random number generation, and user input handling.

Features
Randomly selects a number between 1 and 100 for each game session.

Accepts and validates user guesses through the command line.

Gives instant feedback if the guess is too high or too low.

Displays the number of attempts upon a successful guess.

Error handling for invalid inputs (non-numeric guesses).

How to Run
Ensure Python is installed on your system.

Download or clone the repository and save the script as guessing_game.py.

Open your terminal and navigate to the project directory.

Run the game using:

text
python guessing_game.py
Follow the prompts and start guessing!

Example Session
text
Welcome to the Number Guessing Game!
Guess a number between 1 and 100: 50
Too low! Try again.
Guess a number between 1 and 100: 75
Too high! Try again.
Guess a number between 1 and 100: 60
Congratulations! You guessed it in 3 attempts.
What I Learned
How to use the random module to generate unpredictable results.

Applying loops (while True) to control program flow until a goal is reached.

Validating and converting user input for smooth gameplay.

Providing user-friendly feedback and robust handling for errors.

Counting and displaying attempts for added gamification.

Future Improvements
Limit the number of attempts and display messages for loss case.

Add a replay option after each game session.

Track high scores across multiple rounds.
