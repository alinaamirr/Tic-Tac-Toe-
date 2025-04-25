# Tic-Tac-Toe Game (C Language)

This is a feature-rich **Tic-Tac-Toe game** implemented in **C**, supporting:
- Two-player mode
- AI integration (player vs. AI)
- Three-player mode on a 4x4 board
- Persistent scoreboard saved to a file

## Features

- **Classic 3x3 Two Player Mode**  
  Two players can play against each other. The winner gets to challenge the AI in the next round.

- **4x4 Three Player Mode**  
  Three players compete in a unique 4x4 variant of Tic-Tac-Toe, where symbols X, Y, and Z are used.

- **Player vs. AI Mode**  
  Play against a basic AI that uses simple logic to block or win the game.

- **Persistent Scoreboard**  
  Game outcomes are stored in a file (`scoreboard.txt`) and can be viewed from the menu.

- **Loading Screen & UI Enhancements**  
  Visual effects include loading animation and colored interface using `gotoxy()` and `Beep()` functions.

## File Overview

- `main.c`: Core implementation of the Tic-Tac-Toe game.
- `scoreboard.txt`: Automatically created to store the game results.

## Dependencies

This program uses:

- `<windows.h>` for `gotoxy()` and color handling
- `<conio.h>` for `getch()` and screen control
- `<time.h>` and `<stdlib.h>` for AI randomness
- `<stdio.h>` and `<string.h>` for I/O operations

> ⚠️ This program is designed for **Windows OS** due to dependencies on `windows.h` and `conio.h`.

## How to Compile and Run

1. Open your terminal or command prompt.
2. Compile the code using a C compiler (e.g., GCC):

```bash
gcc main.c -o tictactoe
