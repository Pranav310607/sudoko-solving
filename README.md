# sudoko-solving
this code is based on the solving sudoko in java 
This Java program implements a backtracking algorithm to solve a standard 9x9 Sudoku puzzle. It correctly fills in empty cells (represented by '.') following Sudoku rules.
 Key Functionalities:
  isSafe() Method:
  Checks if placing a digit at a given cell is valid.
      Ensures no repetition in:
      Row
      Column
      3×3 subgrid
   helper() Method:
       Recursively tries placing digits 1 through 9 in empty cells.
  Uses backtracking: if placing a number leads to a dead-end, it backtracks by resetting the cell to '.'.
    solveSudoku() Method:
        Entry point to start solving from cell (0,0).
    printBoard() Method:
        Prints the Sudoku board in a readable 9x9 format.
    main() Method:
        Initializes a sample board with missing values ('.')
        Prints the solved board.
