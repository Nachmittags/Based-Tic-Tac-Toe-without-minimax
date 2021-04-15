# Based-Tic-Tac-Toe-without-minimax.
Tic Tac Toe made in pure JavaScript.
The robot works that way, making decisions based on the following priorities (from the most till the least important):

1- Line up three dots.
2- Fill up the middle of the board.
3- Block the user from lining three dots.
4- Harm to line up three dots in an external square (1,3,5,7,9).

Caveat: The robot shall insert a dot in the place which is the most closer in relation to the user dots.
Exception: If there is two user dots in the square and the distance between both is 4 squares, play on a internal square (2,4,6,8).

5- Play anywhere.
