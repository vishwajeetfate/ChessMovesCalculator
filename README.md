# ChessMovesCalculator

## Overview

**ChessMovesCalculator** is a Unity project that calculates and highlights all possible legal moves for any chess piece selected on a chessboard. It uses Object-Oriented Programming (OOP) principles, design patterns, and good coding practices to ensure clean, maintainable code. The project also extends functionality by highlighting enemy pieces in red, showing pieces that can be captured.

This project is intended to demonstrate structured and organized code rather than focusing on UI/UX elements.

## Features

- Highlights all possible legal moves for any selected chess piece.
- Highlights cells in **red** when an enemy piece is in range for capture.
- Easily configurable starting positions for each chess piece.
- Code structure follows OOP principles and design patterns for scalability and readability.

## Project Structure

The project consists of the following key components:

- **ChessBoardManager**: Manages the board's state, chess piece selection, and move highlighting.
- **ChessPiece** (abstract class): Represents the base class for all chess pieces.
  - **Pawn**, **Rook**, **Knight**, **Bishop**, **Queen**, **King**: Inherit from `ChessPiece` and implement piece-specific movement logic.
- **MoveValidator**: Helper class responsible for validating legal moves, including checks for capturing enemy pieces.
- **HighlightManager**: Handles the visual highlighting of legal move cells.

## How to Use

1. **Clone the repository**: 
   ```bash
   git clone https://github.com/yourusername/ChessMovesCalculator.git
