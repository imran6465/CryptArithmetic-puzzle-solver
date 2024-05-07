# CryptArithmetic-puzzle-solver
=============================

Introduction
------------

### Abstract

Cryptarithmetic puzzles are challenging arithmetic problems where digits are replaced by letters or symbols. Each letter represents a unique digit, and the objective is to find the correct assignment of digits to letters to make the arithmetic equation valid. This project implements a backtracking algorithm to solve cryptarithmetic puzzles efficiently, leveraging logical deduction and constraint satisfaction techniques.

### Scope

The Cryptarithmetic Puzzle Solver project automates the process of solving cryptarithmetic puzzles using computational techniques. It focuses on employing algorithms from constraint satisfaction and optimization to navigate the solution space effectively. The project explores various strategies to enhance efficiency and reduce search time.

Description
-----------

The Cryptarithmetic Puzzle Solver is designed to provide a robust and efficient solution for a wide range of cryptarithmetic puzzles. Key features and strategies include:

*   **Puzzle Input:** Users can enter cryptarithmetic equations using letters or symbols representing digits.
    
*   **Constraint Satisfaction:** The solver ensures that each letter or symbol is assigned a unique digit while respecting puzzle-specific constraints.
    
*   **Algorithmic Strategy:** Utilizes a backtracking algorithm to explore different combinations of digit assignments, intelligently pruning unfeasible paths and backtracking when necessary.
    
*   **Solution Generation:** Once a valid solution is found, the solver displays the assignment of digits to letters or symbols that satisfy the puzzle. Multiple solutions, if existent, can also be provided.
    
*   **Performance Optimization:** Incorporates optimization techniques to handle larger or complex puzzles efficiently.
    
*   **Error Handling:** Includes error handling mechanisms for input validation and detecting unsolvable or invalid puzzles, providing informative error messages.

Output
-----

1.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
SEND
+ MORE
= MONEY
Solution found: 9567 + 1085 = 10652


2.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
JUPITER
+ SATURN
+ NEPTUNE
= PLANETS
Solution found: 358127 + 468051 + 582301 = 1403479


3.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
EARTH
+ MARS
Invalid number of equations. At least 2 and at most 8 equations are required.


4.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
SUN
+ MOON
+ ST4RS
17
= GALAXY
Invalid character '4' in equation. Only letters, spaces, '+' and '=' are allowed.


5.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
APPLE 
+ BANANA 
= CHERRY
Solution found: 35229 + 856735 = 892964


6.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
ABCD
+ BCDE
= DEFGH
Solution found: 1023 + 1234 = 2257


7.
Enter the puzzle equations (press Enter after each equation, and enter a blank line to finish):
X 
+ Y 
= Z
No solution

    

Usage
-----

1.  **Input Puzzle:** Enter the cryptarithmetic puzzle equation using letters or symbols representing digits.
2.  **Run Solver:** Execute the solver to find valid solutions for the puzzle.
3.  **View Solution:** Display the assigned digits corresponding to the letters or symbols that satisfy the puzzle equation.

Implementation Details
----------------------

The project primarily utilizes a backtracking algorithm for solving cryptarithmetic puzzles. It employs logical deduction and constraint propagation techniques to navigate the search space efficiently.

Contributing
------------

Contributions to enhance the solver's functionality or optimize performance are welcome. Please fork the repository, make changes, and submit a pull request.

Acknowledgments
---------------

This project was developed for learning and exploration purposes, focusing on backtracking algorithms and constraint satisfaction techniques.
