# TikTakToe_Java_Game

# TicTacToe_Java_Game

## Project Overview

This project is a simple implementation of the classic Tic Tac Toe game using Java. The game allows a player to play against the computer in a 3x3 grid. The player and the computer take turns to place their marks ('X' for the player and 'O' for the computer) on the grid. The goal is to get three of your marks in a row, either horizontally, vertically, or diagonally.

## Features

- Player vs. Computer gameplay
- Input validation to ensure moves are made to empty spots
- Randomized computer moves
- Detection of win, loss, and draw conditions

## How to Run the Game

1. Ensure you have Java installed on your machine. You can check by running `java -version` in your command line.
2. Compile the Java file by running `javac TicTacToe.java`.
3. Run the compiled class file by executing `java TicTacToe`.

## Code Explanation

### Main Class: `TicTacToe`

This class contains the main method and controls the flow of the game. It consists of several methods:

- `main(String[] args)`: This is the entry point of the game. It initializes the game board, handles player input, and controls the game loop.
- `printGameBoard(char[][] gameBoard)`: This method prints the current state of the game board.
- `placePiece(char[][] gameBoard, int pos, String user)`: This method places a piece on the game board for the specified user (player or computer).
- `checkWinner()`: This method checks if there is a winner or if the game is a draw.

### Detailed Method Descriptions

- `main(String[] args)`: Initializes the game board and starts the game loop. It alternates between player and computer moves until a winner is found or the game ends in a draw.
  - Prompts the player to enter a position.
  - Checks if the entered position is valid and not already taken.
  - Places the player's piece on the game board.
  - Checks for a winner after the player's move.
  - Generates a random valid move for the computer.
  - Places the computer's piece on the game board.
  - Checks for a winner after the computer's move.

- `printGameBoard(char[][] gameBoard)`: Iterates through the game board array and prints the current state, showing the positions of 'X' and 'O'.

- `placePiece(char[][] gameBoard, int pos, String user)`: Converts the user's chosen position to coordinates on the game board and places the corresponding piece ('X' or 'O').

- `checkWinner()`: Checks all possible winning combinations to determine if the player or computer has won, or if the game is a draw.

## Future Enhancements

- Add a graphical user interface (GUI) for a more interactive experience.
- Implement different levels of difficulty for the computer opponent.
- Allow two-player mode where two human players can play against each other.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

[ABu O:]

