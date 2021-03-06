# Sudoku-Solver (console version)
program that solves [sudoku](https://en.wikipedia.org/wiki/Sudoku) in less than a second

## INPUT INSTRUCTIONS
Input the sudoku row by row and use 0 at the place of empty box ([sample inputs](https://github.com/Arsenic-ATG/Sudoku-Solver/blob/master/sample%20input.sty) are already attached)

#### algorithm (backtracking) :- 
It uses recursive calling to find the solution by building a solution step by step increasing values with time. It removes the solutions that doesn't give rise to the solution of the problem based on the constraints given to solve the problem. much better and faster than brute force but still takes a lot of time for larger sudokus.
