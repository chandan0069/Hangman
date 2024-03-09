# Hangman

This Python code implements a fun and challenging Hangman game where you try to guess a secret word letter by letter.

Save the code files as:
hangman.py (main script)
hangman_words.py (list of words to choose from)
hangman_art.py (visual representations of hangman stages)
Run the script: python hangman.py

Gameplay:

The game will start with the classic Hangman logo.
You'll see a row of underscores representing the hidden word's length.
Guess a letter by entering it and pressing Enter.
The game will:
Reveal the guessed letter in the correct positions if it's in the word.
Inform you if you've already guessed that letter.
Deduct a life and display the corresponding hangman stage if your guess is wrong.
The game ends when:
You successfully guess all the letters (win).
You run out of lives (lose).

Key Files:

hangman.py: Main script handling game logic, user interaction, and importing modules.
hangman_words.py: Contains a list of words the game can choose from.
hangman_art.py (Import Required): Provides visual representations of the hangman stages based on remaining lives.
