# AlphaCode21
This Python Hangman game is a console-based program where players guess letters to figure out a randomly chosen word within a limited number of attempts. The code follows these steps:

Setup: A word list of colors is provided, and get_word() selects one at random.

Gameplay: In the play(word) function, the player has 6 attempts to guess either letters or the entire word. Correct guesses reveal letters; incorrect guesses draw parts of a hangman using display_hangman().

Tracking: Guessed letters and words are stored to prevent duplicates.

Loop: main() initiates the game, offering the player the option to play again after each round.

With each incorrect guess, a part of the hangman is drawn until the player either guesses the word or loses.









