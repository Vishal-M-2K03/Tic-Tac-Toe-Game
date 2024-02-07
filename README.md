# Tic-Tac-Toe-Game

# Tic-Tac-Toe Game

## Overview
This is a simple implementation of the classic Tic-Tac-Toe game using Java and Swing for the graphical user interface. The game allows two players to take turns making moves on a 3x3 grid, with the objective of getting three of their symbols in a row (horizontally, vertically, or diagonally). The game declares a winner when one of the players achieves this objective.

## Features
- Graphical user interface using Swing components.
- Two players take turns making moves.
- Winning combinations are highlighted.
- Game announces the winner (X or O) or a draw.
- A delay at the beginning to randomly determine the starting player.

## How to Play
1. Run the `Main` class to start the game.
2. The game window will appear with a 3x3 grid of buttons.
3. Player X starts first, and their moves are marked with a red "X".
4. Player O follows, and their moves are marked with a green "O".
5. The game continues until one player wins or there's a draw.
6. The winning combination will be highlighted, and the game declares the winner.

## Implementation Details
- The game is implemented in Java.
- GUI components are created using Swing (JFrame, JPanel, JButton, etc.).
- Players' moves are handled through the `ActionListener` interface.
- The `check` method determines if there is a winner or a draw after each move.
- The `xWins` and `oWins` methods highlight the winning combination and declare the winner.
- A delay is included at the beginning to randomly determine the starting player.

## Dependencies
- Java Development Kit (JDK) must be installed to run the game.

## How to Run
1. Download the project file and paste it in the Eclipse or Spring tool suite or Netbeans folder after the extraction
2. Run the Main.java

## Future Improvements
- Implement a reset functionality to play multiple rounds without restarting the application.
- Add a menu with options to customize the game settings.
- Improve the user interface and styling for a more polished appearance.

## License
This project is open-source and available under the [MIT License](LICENSE).

Feel free to contribute to the project or use it as a starting point for your own game development projects!
