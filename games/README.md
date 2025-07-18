# Chess Game - User vs Computer

## Project Description
This is a simple web-based chess game where a user plays against a computer AI. The game runs entirely in the browser and features a basic user interface with a chessboard and pieces. The AI opponent uses the minimax algorithm with alpha-beta pruning to select moves.

## How to Run
To play the game, simply open the `index.html` file located in the `chess-game` folder using any modern web browser (such as Chrome, Firefox, Edge, or Safari). No additional setup or installation is required.

## Requirements
- A modern web browser with JavaScript enabled.
- No other software, libraries, or frameworks need to be installed.

## How to Play
- You play as the white pieces, and the computer plays as the black pieces.
- Click on a white piece to select it, then click on a valid destination square to move it.
- The game enforces simplified chess rules (note: no castling, en passant, or promotion).
- The computer will automatically make its move after you make yours.
- The game ends when either king is captured.

## Algorithm Used
The computer AI uses the **minimax algorithm with alpha-beta pruning** to evaluate possible moves and select the best one. This algorithm recursively explores potential future moves up to a limited depth (3 moves ahead) and prunes branches that cannot improve the outcome, optimizing performance while maintaining competitive play.

## Images / Screenshots
No images or screenshots are included in this project. To see the game in action, open the `index.html` file in your browser.

---

Enjoy playing the chess game!
