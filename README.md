# tictactoe
it's an  indoor computer gaming project
The full designing and creating of Tic-Tac-Toe has been executed under windows operating
system, this platform provides a and satisfies the basic need of a good compiler.
Using GL/glut.h library and built in functions make it easy to design good graphics package
such as this simple game.
The following example game is won by the first player, X:

A player can play perfect tic-tac-toe (win or draw) given they move according to the highest
possible moves:
 Win: If the player has two in a row, play the third to get three in a row.
 Block: If the opponent has two in a row, play the third to block them.
 Fork: Create an opportunity where you can win in two ways.
 Block opponent's fork:
 Option 1: Create two in a row to force the opponent into defending, as long as
it doesn't result in them creating a fork or winning. For example, if "X" has a
corner, "O" has the center, and "X" has the opposite corner as well, "O" must
not play a corner in order to win. (Playing a corner in this scenario creates a
fork for "X" to win.)
 Option 2: If there is a configuration where the opponent can fork, block that
fork.

 Center: Play the center.
 Opposite corner: If the opponent is in the corner, play the opposite corner.
 Empty corner: Play in a corner square.
 Empty side: Play in a middle square on any of the 4 sides.
