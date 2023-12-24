INTRODUCTION:
-------------
*	Sudoku: is a logic-based, combinatorial number placement puzzle . The word “Sudoku” is short for Su-ji wa dokushin ni kagiru (in Japanese), which means “the numbers must be single”.
*	Box (Region, Block): A region is a 3x3 box like the one. There are 9 regions in a traditional Sudoku puzzle.
*	Cell (Square): is used to define the minimum unit of the Sudoku board. 
*	Candidates: the number of possible values that can be placed into an empty square. 
*	Clues: the given numbers in the grid at the beginning.
*	Grid (board): The Sudoku board consists of a form of matrix or windows.

  
Backtracking:
------------------------
* Define a global puzzle array.
* Use recursive backtracking to solve the puzzle:
   * If no more choices, the puzzle is solved.
   * Move to the next square if not empty.
   * For each digit 1 to 9:
       If the digit is valid in the current row, column, and box, fill the square and move to the next one.
   * If no valid number is found, backtrack to the previous square.
   * ![image](https://github.com/jha-sakshi/sudoku-solver/assets/95759285/6a5ad5ee-9c35-42be-83fe-b6c88b445e45)


