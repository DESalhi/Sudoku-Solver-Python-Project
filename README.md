# Sudoku Solver

A simple sudoku solver written in Python.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need to have Python installed on your machine to run this project. You can download Python from the official website [here](https://www.python.org/downloads/).

### Installing

Clone or download the repository to your local machine.

git clone https://github.com/DESalhi/Sudoku-Solver.git

Navigate to the project directory and run the script `sudoku_solver.py`.

cd Sudoku-Solver-Python-Project

python sudoku_solver.py

## Usage

The program takes a 9x9 grid of numbers as input, where 0 represents an empty cell. The grid is solved using a backtracking algorithm and the solution is displayed in a graphical format using `tkinter`.

```python
grid = [[5, 3, 0, 0, 7, 0, 0, 0, 0],
        [6, 0, 0, 1, 9, 5, 0, 0, 0],
        [0, 9, 8, 0, 0, 0, 0, 6, 0],
        [8, 0, 0, 0, 6, 0, 0, 0, 3],
        [4, 0, 0, 8, 0, 3, 0, 0, 1],
        [7, 0, 0, 0, 2, 0, 0, 0, 6],
        [0, 6, 0, 0, 0, 0, 2, 8, 0],
        [0, 0, 0, 4, 1, 9, 0, 0, 5],
        [0, 0, 0, 0, 8, 0, 0, 7, 9]]

if solve(grid):
    draw_grid(grid)
else:
    print("No solution found")
```

### Built With
- Python - The programming language used
- tkinter - The GUI library used

### Contributing
Feel free to contribute to this project by submitting a pull request.

### Authors
Dhia Elhak Salhi

### License
This project is licensed under the MIT License.
