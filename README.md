
# Tic Tac Toe Game

## Overview

This is a simple web-based Tic Tac Toe game built using HTML, CSS, and JavaScript. The game consists of two players: Player X and Player O, who take turns marking spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. If all nine spaces are filled without any player winning, the game ends in a draw.

## Features

- **Two-player mode**: X and O take turns to play.
- **Real-time update of turns**: The current player's turn is displayed on the screen.
- **Game Status**: Displays the game result (Winner or Draw).
- **Responsive Design**: The game is responsive to different screen sizes.

## File Structure

```
├── index.html          # The main HTML structure of the game
├── css/
│   └── style.css       # CSS for styling the game board
├── js/
│   └── main.js         # JavaScript to control game logic
├── images/
│   └── chalk-board-bg.jpg  # Background image used in the game
```


## Game Logic

- **Switching turns**: The game alternates between Player X and Player O. 
- **Win Condition**: The game checks for the following winning conditions:
  - Three horizontal cells filled with the same mark (X or O).
  - Three vertical cells filled with the same mark (X or O).
  - Three diagonal cells filled with the same mark (X or O).
- **Draw Condition**: If all the cells are filled and there is no winner, the game is a draw.

### Key JavaScript Functions

- `handleClick(el)`: Handles the user's click on a cell, assigns the current player's mark, and checks for the winner.
- `checkWinner()`: Checks all winning combinations to determine if a player has won or if the game is a draw.


## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)



