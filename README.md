# PRODIGY_SD_04
 
Create a program that solves Sudoku puzzles automatically. The program should take an input grid representing an unsolved Sudoku puzzle and use an algorithm to fill in the missing numbers. 
It should use backtracking or other suitable techniques to explore possible solutions and find the correct arrangement of numbers for the puzzle. Once solved, the program should display the completed Sudoku grid.


explanation: Grid Representation:

The Sudoku grid is represented as a 9x9 array where 0 indicates an empty cell.
isSafe Function:

Checks if placing a number in a particular cell is valid by ensuring the number does not already exist in the same row, column, or 3x3 sub-grid.
solveSudoku Function:

Uses backtracking to solve the puzzle.
Finds an empty cell and tries placing numbers 1-9 in it.
Recursively attempts to solve the puzzle with the current configuration.
If placing a number leads to a solution, it returns true. If not, it backtracks by resetting the cell to 0 and trying the next number.
main Function:

Defines an initial Sudoku puzzle and calls solveSudoku to solve it.
Prints the solved puzzle if a solution is found.
You can compile and run this program using a C compiler like gcc. Adjust the initial grid for different puzzles as needed.

