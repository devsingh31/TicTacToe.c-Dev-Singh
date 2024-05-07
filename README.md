
# Tic-Tac-Toe Game in C

## Introduction
This Tic-Tac-Toe game is a console-based application developed in C. It allows two players to play the classic game of Tic-Tac-Toe on a 3x3 grid. The game provides features like viewing the leader board, dynamic player turn switching, and automated game state checks to determine a win or draw.

## Prerequisites
- A C compiler (GCC recommended)
- Basic knowledge of using terminal or command prompt
- For Windows, environment configured to run C programs

## Compilation and Running
To compile and run this program, follow the steps appropriate for your operating system.

### On Unix-like systems:
1. Open your terminal.
2. Navigate to the directory containing the game's source code.
3. Run the following command to compile the game:
   ```
   gcc -o tic_tac_toe tic_tac_toe.c
   ```
4. To start the game, execute:
   ```
   ./tic_tac_toe
   ```

### On Windows:
1. Open Command Prompt.
2. Navigate to the directory where the game's source code is located.
3. Compile the game using:
   ```
   gcc -o tic_tac_toe.exe tic_tac_toe.c
   ```
4. Run the game by executing:
   ```
   tic_tac_toe.exe
   ```

## Features
- **Start New Game**: Allows two players to enter their names and start a new game. Players can choose their symbols (X or O).
- **View Leader Board**: Displays the game outcomes stored in `score.txt`, showing which player won or if the game was a draw.
- **Dynamic Symbol Assignment**: Players decide whether they want to play as X or O at the beginning of the game.
- **Win Check**: Automatically checks the board after every move to determine if there's a winner.
- **Game Board Display**: Updates and displays the game board after each player's move.
- **Clear and Colorful CLI**: Uses system commands to clear the screen and apply color settings for better readability and aesthetics (specific to Windows).

## Game Rules
The game is played on a grid that's 3 squares by 3 squares. Players take turns putting their marks (X or O) in empty squares. The first player to get 3 of their marks in a row (up, down, across, or diagonally) is the winner. When all 9 squares are full, if no player has 3 marks in a row, the game is considered a draw.

