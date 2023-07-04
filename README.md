# SnakesAndLadders

This is a simple implementation of the popular board game "Snakes and Ladders" using HTML, CSS, and JavaScript.

Files

game.css: Contains the CSS styling for the game.
game.js: Contains the JavaScript code that implements the game's logic.
index.html: The HTML file that structures the web page.
Languages Used

JavaScript: 49.3%
HTML: 33.0%
CSS: 17.7%
Game Implementation

The game board is created using a grid layout in CSS, with each cell of the grid corresponding to a spot on the game board. The board is made up of 100 cells, labeled from 1 to 100. There are two player tokens, represented by the IDs p1 and p2 in the HTML file.

The game's logic is implemented in the game.js file. It uses a turn-based system, with players taking turns to roll a dice and move their token forward by the number of spaces rolled. The game's turn is tracked using a tog variable that increments after each turn.

The play function implements the movement of the player tokens. It takes into account the current player, their current position on the board, and the number rolled on the dice. The function also handles the logic for landing on a snake or a ladder, adjusting the player's position on the board as necessary.

The position of the player tokens is updated using CSS to change the left and top style properties. The game also includes sound effects for rolling the dice and winning the game.

Instructions

To play the game, players click the "ROLL" button to roll the dice. The game alternates between players each turn, and the current turn is displayed on the screen. When a player reaches the 100th cell, they win the game, and an alert is displayed announcing the winner. The page then reloads to start a new game.

Dependencies

The dice rolling sound is loaded from a file named rpg-dice-rolling-95182.mp3.
The win sound is loaded from a file named winharpsichord-39642.mp3.
Please note that these files need to be in the same directory as the game.js file for the sounds to work properly.

Future Enhancements

Possible future enhancements for this game could include a more visually appealing game board, multiplayer functionality, a score tracking system, and more complex rules for the game.

Remember that this implementation is simple and serves as a starting point for more complex versions of the game.
