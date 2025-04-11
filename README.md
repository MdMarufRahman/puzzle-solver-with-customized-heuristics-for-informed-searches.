
## Project Name: Puzzle solver 
### Overview
Puzzle Solver is a Python-based project that solves two classic puzzles:

**8-Puzzle Solver:** Solves the 8-puzzle using multiple search algorithms (Breadth-First Search, Depth-First Search, and A* Search with a Manhattan distance heuristic).

**Sudoku Solver:** Solves Sudoku puzzles using recursive backtracking. The solver offers two variants: Basic Backtracking and Advanced Backtracking with the Minimum Remaining Value (MRV) heuristic.

This puzzle solver allows users to enter their own puzzle setup and choose the algorithm to solve it. They can see the time taken for the algorithm to solve the puzzle, including the number of nodes expanded for the 8-puzzle
### Features
**Multiple Puzzle Types:** Supports both 8-puzzle and Sudoku.

**Algorithm Selection:** Choose from BFS, DFS, or A* for the 8-puzzle and from Basic or Advanced Backtracking for Sudoku.

**Custom Input:** The program asks the user to enter the puzzle setup using the command line.

**Performance Metrics:** Displays results including the solution, nodes expanded (for 8-puzzle), and execution time.

**Modular Design:** The code is organized so it's easy to update and add new features.

### Requirements
Python 3.x
### Input Format
**8-Puzzle:**
Enter 9 numbers (1-8 and 0 for the blank space) separated by spaces.

Example:
1 2 3 4 5 6 7 8 0

**Sudoku:**
Enter 9 lines; each line must have 9 numbers separated by spaces.

Use 0 for empty cells.

Example:

5 3 0 0 7 0 0 0 0

6 0 0 1 9 5 0 0 0

0 9 8 0 0 0 0 6 0

8 0 0 0 6 0 0 0 3

4 0 0 8 0 3 0 0 1

7 0 0 0 2 0 0 0 6

0 6 0 0 0 0 2 8 0

0 0 0 4 1 9 0 0 5

0 0 0 0 8 0 0 7 9

### Code Structure
puzzle_solver.py:

The main file containing:

- The EightPuzzle class and associated search algorithms (BFS, DFS, A*).

- The Sudoku solver functions implementing both basic and advanced backtracking strategies.

- Functions to gather user input for each puzzle type and display formatted output.
