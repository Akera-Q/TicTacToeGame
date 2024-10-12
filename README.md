# TicTacToeGame

First, in the html file, we make a <table> element which contains three rows (3 <tr>) each containing 3 <td> and the nine of these have the class "cells", 
each cell has its own id starting form the top left cell with "0" as an id and ending bottom right with "8" as an id.
After this we add a <div> element which will contain a message when the game ends (for winning, losing or drawing) and it will also contain a button for starting a new game.

In the css file we simply adjust the elements' positions and colors.

In the Javascript file, first off we define a variables: origBoard contains the nine cells(I think). Next we define our constants: huPlayer is "O" and aiPlayer is "X",
then we define each winning combo so the AI knows what to do, the next constant is "cells" which allows us to use the "cell" class without calling it each time.
 Now for functions, the first one "startGame" removes the "endgame" screen, then it passes over each cell and removes any text in it, any background color it optained, 
and adds an event listener that triggers the turnClick function when a cell is clicked.
The turnClick function      ---DELETE LATER<FIRST COMMIT, GONNA REST A BIT(we were asking chatgpt to explain each function)>---
