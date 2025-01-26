# random_word
Welcome to the random_word wiki! This repository contains the coding for four tasks: word_seg, guess_daily, guess_random, and guess_selected.
## Guess Word
The guess word can be from the stuck list or from random generated (it generates a list of random words of the specified length).
Exclude both correct guesses and incorrect guesses from the random selection pool
Program Design:
-Start a game.
-Make guesses with random words.
-Process feedback from the API.
-Repeat until the puzzle is solved or maximum attempts are reached.
For the correct and incorrect character guess, track the character and position. For the correct character, stick it for remaining guess; For the incorrect character, remove it from the guessing pool.
Set the max attempt number, if the word is correctly guessed or reach the max attempt, the process comes to an end.
Feel free to explore the repository and contribute to the project!
