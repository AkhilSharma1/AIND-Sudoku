# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: We use constraint propagation in this case by restricting the number of values in that unit. This happens by 
eliminating the naked twin values from other boxes of that unit which reduces the search space.
 
# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: We use constraint propagation in this case by considering both the diagonals as units which makes sure that numbers 
are not repeated across them.
