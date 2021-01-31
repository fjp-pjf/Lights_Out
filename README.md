# Lights_Out
This is a react-developed game almost similar to the 1024 game.
The game loads with some cells lit.The player has to turn off every lit cell and win the game.On trying to turn off a lit cell, the surrounding cells get non-lit.
ON trying to turn on a non-lit cell other cells get lit.The player has to figure out the correct pattern inorder to win the game.

The game is designed with stateful components and downward data flow and two main components the Board.js and Cell.js.
The child is dumb comapred to the parent.All the main functions are executed through the parent.Several logic is applied to make the neighbouring cells lit and non-lit.
But simplified for anyone  to understand.
