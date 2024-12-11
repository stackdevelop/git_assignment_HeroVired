## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/stackdevelop/git_assignment_HeroVired

# CalculatorPlus (Q1)

CalculatorPlus is a Python application that provides basic arithmetic operations, such as addition, subtraction, multiplication, division, and calculating the square root of a number.

## Features
- **Addition**: Add two numbers.
- **Subtraction**: Subtract one number from another.
- **Multiplication**: Multiply two numbers.
- **Division**: Divide one number by another (with error handling for division by zero).
- **Square Root**: Calculate the square root of a given number.

# Git LFS (Q2)

This solution demonstrates the integration of Git LFS (Large File Storage) to manage large binary files efficiently in Git repositories.

## 1. Notes
- Checkout to the branch:
   ```bash
   git checkout lfs
- Install Git LFS on your machine by running:
  ```bash
  git lfs install
- This was the command which used to track the .bin files:
  ```bash
    git lfs track "*.bin"
    .gitattributes keeps the track of it
- Code for adding a large file to repo:
    ```bash
    git add large_file.bin
    git commit -m "Add large binary file"  

# Geometry Calculator (Q3)

The Geometry Calculator is a Python program that calculates:
- The area of a circle.
- The area of a rectangle.

This solution demonstrates how to use Git branching and stashing to work on multiple features simultaneously without committing incomplete changes.

## Features
1. **Calculate Circle Area**: Computes the area of a circle given its radius.
2. **Calculate Rectangle Area**: Computes the area of a rectangle given its length and width.



# Special Notes:
There are a few additional commits aimed at improving the structure and enhancing clarity. These changes will benefit developers by making the codebase more organized and easier to work with. Additionally, screenshots have been provided in the screenshots folder, which is available in both the dev and main branches.


