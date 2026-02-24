🧩 Sudoku Solver – C++ (Internship Project)
📌 Project Overview

The Sudoku Solver is a console-based C++ application developed as part of my internship tasks.
This program uses a backtracking algorithm to solve any standard 9×9 Sudoku puzzle by filling empty cells while following Sudoku rules.

It demonstrates recursion, constraint checking, and algorithmic problem-solving in C++.

⚙️ Features

✔ Solve any standard 9×9 Sudoku puzzle
✔ Represents the puzzle as a 2D array
✔ Checks for row, column, and 3×3 subgrid constraints before placing a number
✔ Uses backtracking to explore possible solutions
✔ Recursively fills the grid until the puzzle is solved
✔ Displays the solved Sudoku grid

🧠 Algorithm Overview

Find an empty cell in the grid (represented by 0).

Try numbers 1–9 in the empty cell.

Check if the number is safe:

Not present in the same row

Not present in the same column

Not present in the 3×3 subgrid

If safe, place the number and recursively solve the rest of the grid.

If a number leads to no solution, backtrack and try the next number.

Repeat until the grid is completely filled or determined unsolvable.

🖥 Example Input/Output

Input (0 represents empty cells):

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9

Output:

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
🛠 Technologies Used

C++

2D Arrays

Recursion and Backtracking

Console-based User Interface

💡 Skills Demonstrated

Implementation of backtracking algorithms

Constraint checking (row, column, 3×3 subgrid)

Recursion and logical problem solving

Handling 2D arrays and user input

Algorithm design for puzzle solving

▶ How to Run

Compile the program using any C++ compiler:

g++ sudoku_solver.cpp -o sudoku_solver

Run the executable:

./sudoku_solver

Enter the Sudoku puzzle row by row (use 0 for empty cells).

👩‍💻 Author

Hiba Zia
Internship Project – Code Alpha
