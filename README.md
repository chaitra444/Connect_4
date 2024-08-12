Connect Four Game

This is a Connect Four game implemented using Python and Pygame. Connect Four is a two-player board game where the players take turns dropping colored discs into a grid, with the goal of connecting four of their own discs in a row, either horizontally, vertically, or diagonally.

Features

Two-Player Mode: Players take turns to drop discs into the columns.
Win Detection: The game detects when a player has connected four discs in a row and announces the winner.
Graphical Interface: The game uses Pygame to provide a visual representation of the board and player moves.
Requirements
Python 3.x
Pygame library
You can install Pygame using pip:

bash
Copy code
pip install pygame
Game Instructions
Start the Game: Run the connect_four.py script.
Player Turns: Player 1 uses pink discs, and Player 2 uses white discs.
Drop Discs: Click on a column to drop a disc into that column. The disc will fall to the lowest available row in that column.
Winning: The game will announce the winner when a player connects four discs in a row horizontally, vertically, or diagonally.
Game Over: The game will display the winning message for 5 seconds before closing.
