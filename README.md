# Sudoku Solver

This project is a simple Sudoku solver implemented in C++. It uses a backtracking algorithm to solve Sudoku puzzles. The program includes 10 predefined Sudoku puzzles and allows the user to choose one to solve.

## Features

- Solves any 9x9 Sudoku puzzle using a backtracking algorithm.
- Includes 10 different Sudoku puzzles.
- Allows the user to select a puzzle to solve.
- Prints the solved Sudoku puzzle.

## Requirements

- A C++ compiler (e.g., g++, clang++)
- C++ Standard Library

## How to Use

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/sudoku-solver.git
    cd sudoku-solver
    ```

2. **Compile the code:**

    ```bash
    g++ sudoku_solver.cpp -o sudoku_solver -lm
    ```

    Note: The `-lm` flag is used to link the math library for the `sqrt` function.

3. **Run the program:**

    ```bash
    ./sudoku_solver
    ```

4. **Select a Sudoku puzzle to solve:**

    When prompted, enter a number between 1 and 10 to select one of the predefined Sudoku puzzles. The program will then solve the selected puzzle and display the solved board.

## Example

When you run the program, you will see a prompt like this:

Select a Sudoku puzzle to solve (1-10):


Enter a number between 1 and 10 to select a puzzle. The program will then solve the selected puzzle and print the solved board.

## Code Overview

### Functions

- **print(int board[][9], int n)**: Prints the Sudoku board.
- **isvalid(int board[9][9], int i, int j, int num, int n)**: Checks if placing `num` at position `(i, j)` is valid.
- **Sudokusolver(int board[9][9], int i, int j, int n)**: Solves the Sudoku puzzle using backtracking.

### Main Function

The `main` function initializes 10 different Sudoku puzzles and asks the user to select one to solve. It then calls `Sudokusolver` to solve the selected puzzle and prints the result.


## Author

- Nishank Sahu - [Nishank16](https://github.com/Nishank16)

## Acknowledgments

- This project was inspired by the classic Sudoku puzzles.
