# Minesweeper

A Minesweeper game that you can play by yourself or let AI play for you.

**Note:** AI will not always win! There will be some cases where the AI must guess, because it lacks sufficient information to make a safe move. On terminal, there will print whether the AI is making a move it believes to be safe or whether it is making a random move.


![Demo](https://media.giphy.com/media/kmtNz8MeSy52eFXGaj/giphy.gif)


## Installation

Run `pip3 install -r requirements.txt` to install pygame.



## Getting Started

`cd` to the directory and run `python3 runner.py` to start playing!


## Project description

It is one of the projects for Harvard's online course **CS50’s Introduction to Artificial Intelligence with Python**. There are two main files in this project: `runner.py` and `minesweeper.py`. `runner.py` was implemented by the teaching staff, and contains all of the code to run the graphical interface for the game. In `minesweeper.py`, the `Minesweeper` class was entirely implemented by the teaching staff.
I implemented `hash`, `known_mines`, `known_safes`, `mark_mine`, and `mark_safe` functions in the `Sentence` class, and `add_knowledge`, `neighbors`, `make_safe_move`, and `make_random_move` functions in the `MinesweeperAI` class.
