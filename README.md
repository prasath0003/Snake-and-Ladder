# Tic Tac Toe Game

## Overview
This is a simple command-line implementation of the classic Tic Tac Toe game. The game is played between two players, X and O, who take turns to mark spaces in a 3x3 grid. The first player to align three of their marks horizontally, vertically, or diagonally wins the game. If all nine spaces are filled without a winner, the game ends in a tie.

## Features
- Player vs Player mode.
- Clear display of the game board with positions for easy reference.
- Input validation to ensure that moves are made in available spots only.
- Automatic detection of the winner or tie.

## How to Play
1. Run the game script in a Python environment.
2. Player X starts the game by choosing a position from 1 to 9 on the grid.
3. Player O then takes their turn.
4. The game continues until one player wins or all positions are filled resulting in a tie.
5. The result is displayed at the end of the game.

## Code Structure
- `board`: A list representing the 3x3 grid where players make their moves.
- `game_still_going`: A boolean variable that keeps track of whether the game is still in progress.
- `winner`: A variable that holds the winner of the game or None if it's a tie.
- `current_player`: Tracks whose turn it is (either "X" or "O").

### Functions
- `play_game()`: Manages the flow of the game.
- `display_board()`: Displays the current state of the game board.
- `handle_turn(player)`: Handles the logic for a player's turn.
- `check_if_game_over()`: Checks whether the game has ended.
- `check_for_winner()`: Determines if there is a winner.
- `check_rows()`, `check_columns()`, `check_diagonals()`: Check for wins in rows, columns, and diagonals, respectively.
- `check_for_tie()`: Checks if the game is a tie.
- `flip_player()`: Switches the current player after each turn.

## Installation
1. Ensure you have Python installed (version 3.6 or higher).
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
