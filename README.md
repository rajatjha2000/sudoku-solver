# Sudoku-Solver
Sudoku Solver with the help of **Backtracking Algorithm**.

**Backtracking** is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. 
We will use this principle of backtracking to implement the following algorithm.

**Algorithm**:-

1. Starting with an incomplete board
2. Find some empty space
3. Attempt to place the digits 1-9 in that space
4. Check if that digit is valid in the current spot based on the current board
5. a. If the digit is valid, recursively attempt to fill the board using steps 1-3.\
   b. If it is not valid, reset the square you just filled and go back to the previous step.
6. Once the board is full by the definition of this algorithm we have found a solution.

