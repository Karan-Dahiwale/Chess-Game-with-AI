
# Chess (PvP) Game
A two-player chess game developed in Python using Pygame. This project allows two players to play chess against each other, with built-in rule validation for all pieces, including captures and checkmate detection.


## Features


- **Two-player PvP gameplay**: Play against another person on the same computer.
- **Piece movement validation**: Each chess piece moves according to its official rules.
- **Capture detection**: Automatically detects and handles piece captures.
- **Checkmate detection**: Identifies checkmate conditions and ends the game accordingly.
- **Efficient performance**: Capable of handling over 1,000 moves without performance issues.
- **Real-time updates**: The chessboard updates in real time as players make their moves.


## Prerequisites

To run this game, ensure you have the following installed:

- Python 3.12

- Pygame library

You can install Pygame using the following command:

```bash
  pip install pygame
```




## Installation


- clone the repository
```bash
  git clone https://github.com/Karan-Dahiwale/Chess-Game-with-AI.git

```
   - Navigate to the project directory

   ```bash
 cd Chess-Game-with-AI

```
## usage

To start the game, run the main.py script:

   ```bash
 python main.py

```
The game window will open, and you can begin playing by clicking on pieces to move them.
## Gameplay

- Click to select a piece, and then click on a valid destination square to move it.

- The game validates the moves in real-time, ensuring that only legal moves are allowed.

- The game will notify you if a player is in check or checkmate.

## Game Rules

- **Pawn**: Moves one square forward, but captures one square diagonally. It can move two squares forward on its first move.
- **Rook**: Moves any number of squares horizontally or vertically.
- **Knight**: Moves in an "L" shape: two squares in one direction and then one square perpendicular.
- **Bishop**: Moves any number of squares diagonally.
- **Queen**: Moves any number of squares horizontally, vertically, or diagonally.
- **King**: Moves one square in any direction.



## Contributing
  If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!
