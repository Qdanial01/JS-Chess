# JS Chess

This is a simple chess game built with JavaScript. The game features the ability to move chess pieces on a board, drag them, and check for valid moves. It uses HTML, CSS, and JavaScript for its functionality.

## Project Overview

This project consists of 4 main files:

- **`index.html`**: The base HTML page for the chess game interface.
- **`style.css`**: The CSS file for styling the game, including the design, size, colors of the board and pieces, and tile configurations.
- **`app.js`**: Contains the logic for initializing the game, setting up the pieces, managing piece movements, validating moves, checking for check and checkmate conditions, and managing player turns.
- **`pieces.js`**: Holds the SVG links for all the chess pieces used in the game.

## Features

- **Chessboard Layout**: The game board is visually represented using HTML and CSS. It consists of 8x8 squares, colored alternately.
- **Piece Movement**: Each piece can be moved according to the rules of chess. The drag-and-drop functionality is implemented using JavaScript.
- **Turn Management**: The game tracks whose turn it is, ensuring that players alternate between moves.
- **Piece Types**: All standard chess pieces are available: King, Queen, Rook, Knight, Bishop, and Pawn.

## How It Works

1. **Board Setup**: Chessboard is instantly displayed with all its pieces placed on their initial positions.
2. **Drag-and-Drop**: Pieces can be dragged across the board. The move is validated based on the type of piece being moved and the validity of the move.
3. **Turn Tracking**: Each player takes turns, and only the correct player can make a move during their turn.
4. **Validating Moves**: Each piece has its specific movement pattern, and the game checks if the move is valid.
5. **Victory Check**: The game includes functionality to check if a player has won by checking if any one of the 2 kings is left standing.

## Files Breakdown

- **index.html**: This file serves as the interface for the game, holding the structure of the chessboard.
- **style.css**: Contains the design specifications for the chessboard and pieces, such as color, size, and the arrangement of tiles.
- **app.js**: This file manages the logic behind:
  - Initializing the chess pieces
  - Handling piece movement (including drag-and-drop)
  - Validating moves according to chess rules
  - Tracking whose turn it is
  - Checking for checkmate and other end-game conditions
- **pieces.js**: Contains SVG links for the chess pieces used in the game.

## Known Issues

- Currently, the **Queen** and **Rook** pieces do not move as expected. They are only able to move one tile straight, and any attempt to move them beyond one square returns an error in the console. Might work on it for a future update.

## Project Reference

This project was built based on the tutorial by [CodewithAniaKubów](https://www.youtube.com/watch?v=Qv0fvm5B0EM&list=PL1xF_OoSJsKqAgWBjfBIg2Cwc2Fhqsa0L&index=4&ab_channel=CodewithAniaKub%C3%B3w). I highly recommend checking out the video for a deeper understanding of how the game was built.

## How to Run

To run this project locally:

1. Clone the repository or download the files.
2. Open `index.html` in your preferred web browser.

No additional setup is required. The game will load automatically.

