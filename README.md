# Tic-Tac-Toe-Java-Tournament
A modular, console-based Java implementation of the classic Tic-Tac-Toe tournament game featuring custom player profiles, real-time board rendering, dynamic statistics tracking, and competitive tournament rounds.
# Console-Based Tic-Tac-Toe Tournament (Java)

A clean, object-oriented, and interactive console-based **Tic-Tac-Toe** game implemented in Java. This project goes beyond a single match, offering a full **Tournament Mode** where two players can battle across multiple rounds, track their wins/losses/draws, and dynamically reset or restart the tournament.

## 🚀 Features

* **Object-Oriented Architecture:** Designed using clean OOP principles with modular classes (`Board`, `Player`, `HumanPlayer`, `TicTacToe`, `Main`).
* **Tournament System:** Support for multiple continuous rounds with automatic starting-player alternation every round.
* **Dynamic Stats Tracking:** Tracks individual player statistics including overall Wins, Losses, and Draws.
* **Robust Input Validation:** Built-in error handling to catch invalid inputs (e.g., entering letters instead of numbers, or choosing a cell that is already taken).
* **Beautiful Console UI:** Uses clean Unicode/ASCII text formatting to display a clear game board and distinct scoreboard summaries.
* **Advanced Game Loop:** Allows players to decide whether to continue to the next round, reset the score, or restart the entire tournament with the same player names.

## 🛠️ Project Structure

The project consists of the following key components:
* **`Main.java`**: The entry point that instantiates and launches the game controller.
* **`TicTacToe.java`**: The core game engine managing tournament loops, score calculations, and round progressions.
* **`Board.java`**: Handles the $3 \times 3$ grid logic, symbol placements, validation checks, and rendering the visual board.
* **`Player.java`**: An abstract base class defining core player structures, fields (name, symbol, wins, losses, draws), and statistics presentation.
* **`HumanPlayer.java`**: Extends `Player` to manage interactive user input via `Scanner` and filter out invalid moves.

## 🎮 How to Play

1. Run the `Main` class.
2. Enter the names for **Player 1 (X)** and **Player 2 (O)**.
3. On your turn, enter the row and column coordinates separated by a space (e.g., `1 2` for the first row, second column).
4. The game will automatically detect wins or draws, update the statistics, and prompt you for the next action!

## ⚙️ Requirements

* Java Development Kit (JDK) 8 or higher.
* Any standard terminal or IDE (IntelliJ IDEA, Eclipse, VS Code).
