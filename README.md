# Linear-Algebra
Dive into my MATLAB solver for linear systems. This solo venture offers a deep dive into matrix transformations, addressing single, multiple, and no-solution scenarios with pure, crafted code.


This project presents a MATLAB application designed to analyze and solve different types of linear systems. Leveraging matrix operations and transformations, the application can handle three categories of systems: those with unique solutions, those with infinite solutions, and inconsistent systems. Each system is represented by matrices and is handled as follows:

Unique Solution Systems: Determined by Gaussian elimination, ensuring the matrix is square (15x15) and utilizing back substitution to find a unique solution set.
Infinite Solution Systems: These are rectangular (10x15) matrices. The algorithm identifies free variables and provides a general solution, with a specific instance where all free variables are set to one.
Inconsistent Systems: Detected during the transformation process when the matrix row operations indicate no possible solutions.
The code forbids the use of built-in functions, relying on custom implementation for elementary row operations, matrix inversion, and rank calculations. The main function, analyzeSystem, takes a matrix input, applies row operations, determines the rank and consistency of the system, and outputs the final matrix along with a description of the system's consistency and a specific solution if applicable.

This project was developed as a solo effort, and it showcases proficiency in numerical methods, matrix algebra, and programming skills in MATLAB.
