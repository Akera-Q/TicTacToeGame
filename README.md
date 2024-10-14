# TicTacToeGame

  First, in the html file, we make a <table> element which contains three rows (3 <tr>) each containing 3 <td> and the nine of these have the class "cells", 
each cell has its own id starting form the top left cell with "0" as an id and ending bottom right with "8" as an id.
After this we add a <div> element which will contain a message when the game ends (for winning, losing or drawing) and it will also contain a button for starting a new game.

  In the css file we simply adjust the elements' positions and colors.

  In the Javascript file, first off we define a variables: origBoard contains the nine cells(I think). Next we define our constants: huPlayer is "O" and aiPlayer is "X",
then we define each winning combo so the AI knows what to do, the next constant is "cells" which allows us to use the "cell" class without calling it each time.
  Now for functions, the first one "startGame" removes the "endgame" screen, and creates an array from the variable called origBoard which consists of 9 elements for each square,
then it passes over each cell and removes any text in it, any background color it optained, and adds an event listener that triggers the turnClick function when a cell is clicked.
  The turnClick function first checks to see if the cicked square still has a value of a number (not yet assigned to X nor O), if it holds a value of X or O nothing happens, 
but if it's still a free square with a number for a value it gives it an X or an O depending on the whcih player clicked it, the human(huPlayer) of the AI(aiPlayer) with the help of
turn function, it also checks to see if a tie happend using the checkTie function, if it's not a tie the AI makes its move and the game continues.
  The turn function      ---DELETE LATER<FIRST COMMIT, GONNA REST A BIT(we were asking chatgpt to explain each function)>---
