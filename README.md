# Tic-Tac-Toe

## Overview

This is a simple implementation of the Tic-Tac-Toe game in C++. The game allows the user to play against the computer or another human player.

## Features

- Two-player mode (Human vs Human)
- Single-player mode (Human vs Computer with a basic AI)

## How to Play

1. Clone the repository to your local machine.
2. Compile the code using a C++ compiler.
3. Run the compiled executable.
4. Follow the on-screen instructions to play the game.

## Code Structure

- `tictactoe.cpp`: Contains the main logic for the game.

## Instructions

- The game board is a 3x3 grid, and players take turns to place their symbol ('X' or 'O') in an empty cell.
- The game ends when one player wins by getting three in a row horizontally, vertically, or diagonally, or when the board is full, resulting in a draw.

## Compilation

```bash
g++ tictactoe.cpp -o TicTacToe
