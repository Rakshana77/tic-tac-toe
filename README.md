# tic-tac-toe

# Tic-Tac-Toe Game 🎮

A simple implementation of the classic **Tic-Tac-Toe** game using vanilla JavaScript, HTML, and CSS. This game allows two players to take turns placing "X" and "O" on a 3x3 grid until one player wins or the game ends in a draw.

## Features ✨
- **Interactive Gameplay**: Players alternate turns, and the game checks for a winner or draw after each move.
- **Winning Detection**: Detects and displays when a player wins or if the game ends in a draw.
- **Reset Functionality**: Easily restart the game with a reset button.
- **Player Status**: Displays whose turn it is.

## How It Works 🔍
1. **Grid Setup**: A 3x3 board is dynamically created using JavaScript.
2. **Player Turns**: Players take turns clicking on cells to place their marker ("X" or "O").
3. **Win/Draw Detection**: Checks for winning combinations or a draw after each move.
4. **Reset Button**: Clears the board and starts a new game.

## Game Logic 🧠
### Winning Conditions:
The game checks the following combinations for a win:
- **Rows**: [0, 1, 2], [3, 4, 5], [6, 7, 8]
- **Columns**: [0, 3, 6], [1, 4, 7], [2, 5, 8]
- **Diagonals**: [0, 4, 8], [2, 4, 6]

### Key Functions:
- **`createBoard()`**: Initializes the game board and resets the game state.
- **`handleCellClick(event)`**: Handles player moves, updates the game state, and checks for a winner or draw.
- **`checkWinner()`**: Checks if the current player has won.
- **`resetButton` Event Listener**: Resets the game when clicked.

## How to Run 🏃‍♂️
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/tic-tac-toe.git
   cd tic-tac-toe
Open index.html in your browser to play the game:
open index.html
