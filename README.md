# ai-project

Tic-Tac-Toe Solver

Introduction

This is a simple Tic-Tac-Toe game implemented in Python. The game allows a human player ('X') to play against an AI ('O'), which makes optimal moves using the Minimax algorithm.

How to Play

Run the script in a Python environment.

The game board is displayed with empty spaces.

The user is prompted to enter their move by specifying the row and column (1-3).

The AI makes its move automatically.

The game continues until a winner is found or the game ends in a draw.

Input Format

Enter two numbers separated by a space, representing the row and column where you want to place your move.

Example: 1 2 (Places 'X' in row 1, column 2)

Example Gameplay

Enter row and column (1-3): 1 1
X  |   |  
------------
   |   |  
------------
   |   |  

AI moves...
X  |   | O
------------
   |   |  
------------
   |   |  

Winning Conditions

A player wins if they place three of their marks ('X' or 'O') in a row, column, or diagonal.

If all spots are filled without a winner, the game results in a draw.

Features

Simple user input (1-3 for row and column)

AI plays optimally using Minimax algorithm

Displays the board after each move

Detects win and draw conditions automatically

Running the Script

Make sure you have Python installed, then run:

python tic_tac_toe.py

Enjoy the game!

