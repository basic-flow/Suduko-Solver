# Sudoku Solver in Python

[![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A Python implementation of a backtracking algorithm to solve 9×9 Sudoku puzzles.

## Example

![Screenshot 2025-03-28 150902](https://github.com/user-attachments/assets/39e9fe84-f5ea-45bc-82f8-f53912204b70)

## Features

- Solves standard 9×9 Sudoku puzzles
- Uses recursive backtracking algorithm
- Clear visualization of the solving process
- Handles both solvable and unsolvable puzzles
- Easy-to-use interface

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/sudoku-solver-python.git
cd sudoku-solver-python
```
2.Ensure you have Python 3.7+ installed

## Usage

**Define your puzzle (0 represents empty cells)**

```bash
puzzle = [
    [8, 0, 0, 0, 0, 0, 0, 0, 0],
    [0, 0, 3, 6, 0, 0, 0, 0, 0],
    [0, 7, 0, 0, 9, 0, 2, 0, 0],
    [0, 5, 0, 0, 0, 7, 0, 0, 0],
    [0, 0, 0, 0, 4, 5, 7, 0, 0],
    [0, 0, 0, 1, 0, 0, 0, 3, 0],
    [0, 0, 1, 0, 0, 0, 0, 6, 8],
    [0, 0, 8, 5, 0, 0, 0, 1, 0],
    [0, 9, 0, 0, 0, 0, 4, 0, 0]
]
```
## How It Works

The solver uses a backtracking algorithm which:

Finds the next empty cell

Tries numbers 1-9 in the cell

Checks if the number is valid (no conflicts in row, column, or 3×3 box)

Recursively attempts to solve the rest of the board

Backtracks if a solution path fails

## Requirements

**Python 3.7 or higher**
No external dependencies

## Support

If you find this project useful and would like to support its development, you can:

⭐ **Star the Repository:** Show your appreciation by starring this project on GitHub.

💬 **Provide Feedback:** Open an issue or discussion to share your thoughts or suggestions.

🤍 **Donate via PayPal:** If you'd like to support me financially, you can donate via PayPal:
[![PayPal](https://img.shields.io/badge/Donate-PayPal-blue?logo=paypal)](https://paypal.me/basic1man?country.x=MA&locale.x=en_US)


## Author

**Mohamed Moukbil**

