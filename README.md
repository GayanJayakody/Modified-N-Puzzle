# Modified-N-Puzzle

This code is to solve the modified N puzzle problem where there are two empty spaces. Code accepts a Modified N Puzzle in a text file in a form like:
1   4   -   7
9   2   3   5
6   -   10   13
8   11   14   12
and a goal in a text file like:

1   4   7   5
9   2   3   -
-   11   10    13
6   8   14    12

and gives the steps to solve the puzzle. Output will be written to file which contains which number you have to move to which direction.

Total Manhatton heuristic is used as a default huestic. You can change the heuristic to total misplaced tiles by carefully examine the code.
