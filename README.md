# miracle-sodoku

Using z3py and only boolean variables, solve the Miracle Sudoku (spoiler). In this puzzle normal Sudoku rules apply in addition to the following rules:     

Any two cells separated by a knight's move from chess (moving forward two boxes and over one, in any direction) cannot contain the same digit (see image below).    
Any two cells separated by a king's move from chess (one box in any direction including diagonals) cannot contain the same digit.     
Any two orthogonally adjacent (up, down, left, or right) cells cannot contain consecutive digits.
