# Chess Game - University Project

This is a simple chess game developed in C++ that runs entirely on the terminal, without graphical interfaces. It was created as part of a university project at second year. The game supports all basic chess functionalities, but there is a known rare bug that may cause a loop.

## Features
- Terminal-based gameplay.
- Input system to move pieces using standard chess notation.
- Ability to display the chessboard on demand using the `XX XX` command after each move.

## How to Play
1. Clone the repository:
   ```bash
   git clone https://github.com/AndreaBruzz/Chess-Game.git
   ```
2. **Compile the game** using `CMake` or your preferred compiler.
3. **Run the executable** to start playing.

## Known Issues
- Occasionally, the game may enter a loop due to an unresolved bug.
- By default, the chessboard is not shown after every move; use `XX XX` to display it.
