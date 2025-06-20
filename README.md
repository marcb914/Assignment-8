﻿# Assignment-8: Evil Wordle
Evil Wordle is a command-line twist on the classic Wordle game where the computer cheats. Instead of picking a single secret word at the start, the program maintains a pool of possible valid words and adapts its feedback after each guess to delay commitment and make winning as hard as possible.

This project was developed in Python as part of a course assignment at the University of Texas. It demonstrates concepts in algorithm design (merge sort), data structures, ANSI color formatting for CLI games, and object-oriented programming.

evil_wordle.py: Main game logic, color handling, keyboard state, word family mechanics, and feedback engine.

valid_guesses.txt: List of allowed guesses (must be present in the working directory).

test_guesses.txt: Alternate word list for debugging.
