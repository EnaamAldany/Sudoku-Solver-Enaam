# Sudoku-Solver-Enaam
Sudoku Solver in java using Backtracking and CSP algorithms

Sudoku Solver Application:
A Java application for finding solutions for the traditional Suodku game. 
It also determines if the board state is valid, in addition to whether a solution exists at all 

The output of my program :

| 5  8  - | 2  -  - | 4  7  - 
| -  2  - | -  -  - | -  3  - 
| -  3  - | -  5  4 | -  -  - 
----------|---------|----------
| -  -  - | 5  6  - | -  -  - 
| -  -  7 | -  3  - | 9  -  - 
| -  -  - | -  9  1 | -  -  - 
----------|---------|----------
| -  -  - | 8  2  - | -  6  - 
| -  7  - | -  -  - | -  8  - 
| -  9  4 | -  -  6 | -  1  5 
AFTER SOLVING : 
| 5  8  9 | 2  1  3 | 4  7  6 
| 4  2  6 | 9  8  7 | 5  3  1 
| 7  3  1 | 6  5  4 | 8  9  2 
----------|---------|----------
| 9  4  3 | 5  6  8 | 1  2  7 
| 1  6  7 | 4  3  2 | 9  5  8 
| 2  5  8 | 7  9  1 | 6  4  3 
----------|---------|----------
| 3  1  5 | 8  2  9 | 7  6  4 
| 6  7  2 | 1  4  5 | 3  8  9 
| 8  9  4 | 3  7  6 | 2  1  5 



 public static void main(String[] args) {
        //The digit 0 helps us in identifying which place is for the user to fill.
        int[][] arr = {{5, 8, 0, 2, 0, 0, 4, 7, 0},
        {0, 2, 0, 0, 0, 0, 0, 3, 0},
        {0, 3, 0, 0, 5, 4, 0, 0, 0},
        {0, 0, 0, 5, 6, 0, 0, 0, 0},
        {0, 0, 7, 0, 3, 0, 9, 0, 0},
        {0, 0, 0, 0, 9, 1, 0, 0, 0},
        {0, 0, 0, 8, 2, 0, 0, 6, 0},
        {0, 7, 0, 0, 0, 0, 0, 8, 0},
        {0, 9, 4, 0, 0, 6, 0, 1, 5}};

        print(arr, arr.length);     //this is my function to prints the sudoku
        sudokuSolver(arr);//this is my function To solve the sudoku
        System.out.println("AFTER SOLVING : ");
        print(arr, arr.length);} //this is my function to prints the sudoku Solver




It was easy to solve sudoku with backtraking and CSP 
Programming a game that I love was fun

How to Determine the unassigned position
The isSafe function checks for simultaneous satisfaction of check in box 3*3
Representation the sudoku solver


The duration of the project was six days in terms of writing the code, 
understanding it, searching for information about it, and writing a report


I am Enaam Jamal AlDany, I acknowledge that I did not get any help or code 
from any student and that this project is of my own effort
I do not forget that I faced some difficulty, so I searched online to solve some problems, 
and references were put in place that helped me in the search process.
