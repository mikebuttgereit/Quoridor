# Quoridor

Board is 9x9. Individual tiles that pieces goes on. Walls go in between pieces. Walls should be the size of two tiles. Colored pawns, one for each player.

Objective of the game is to move your pawn to the other side of the board (your opponent's side). On their turn, player can either move their pawn U,D,L,R OR they can place a wall on the board. You cannot completely block a player's path to the other side using the walls. There must be a path for them to win. Walls must be placed between two sets of tiles. 

If a player's pawn is facing another player's pawn, they may jump it and advance two spaces. 

Creating the board: 
--Make a 9x9 grid of squares. Have a gamepiece that is conditionally rendered depending on the player's turn and the placement of the piece.

It starts row 1, column 5. If we move it to 1-4, that square turns into a piece and the previous one renders as a square. 

Create buttons for the players to move their pieces up, down, left, or right. If it goes off the board or is blocked by a wall, render an error message. 
