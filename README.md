# Tic-tac-toe
This creates a Tic-tac-toe game in JavaScript. 
## Game Board
HTML and CSS are used to render the game board. The game board is a 3 x 3 grid, numbered 0 to 9, from left to right. It is also lettered *a* to *i*.

## The *game* object
The *winPatterns* array in the *game* object has an array for every winning combination possible. Example, *[a,b,c]* is a winning combination.

## The *user* object
user_x places a "x" on the board, while user_o places a "o".

## Gameplay
The user taking his turn will place his marker ("x" or o" on an empty square (before taking any action, the *board* array of the *game* object is checked to ensure that the square is blank). The *board* and *winPatterns* array is then updated. *winPatterns" is then checked to see if any of the arrays contain all "x" or "o". If so, the winner is declared. Otherwise, move control over to the other player.

*Note*: There is no AI for this. The computer uses a random number generator to determine which square it plays. Possible improvement for future.
