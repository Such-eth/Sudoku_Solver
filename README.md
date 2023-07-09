# Sudoku_Solver
This is a Sudoku solver program implemented in Java using the backtracking algorithm and recursion. It allows you to solve Sudoku puzzles of various difficulties by automatically filling in the missing numbers.

# How to Use
1. Clone the repository to your local machine:.
2. Open the project in your favorite Java IDE.

3. Locate the SudokuSolver.java file and open it.

4. In the main method, you will find a Sudoku puzzle grid represented as a 2D array. Edit the values in the array to match your Sudoku puzzle. Use 0 to represent empty cells.

5. Run the program. The Sudoku solver will attempt to fill in the missing numbers.

6. After the program finishes executing, the solved Sudoku puzzle will be displayed in the console.

# Algorithm
The Sudoku solver uses a backtracking algorithm combined with recursion to find the solution. The backtracking algorithm works as follows:

-> Find an empty cell in the Sudoku grid.\
-> Try each number from 1 to 9 in that cell.\
-> If the number is valid in the current position, move to the next empty cell and repeat steps 1-3.\
-> If none of the numbers are valid in the current position, backtrack to the previous cell and try a different number.\
-> Repeat steps 1-4 until a solution is found.\
-> The algorithm effectively explores all possible combinations of numbers until a valid solution is found or all possibilities are exhausted.

# Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.


# Acknowledgments
> The backtracking algorithm used in this project is a well-known technique for solving Sudoku puzzles.\
> Thanks to the Java programming language for providing the necessary tools and libraries to develop this Sudoku solver.
