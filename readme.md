Introduction to Artificial Intelligence
Task: N-Queen Problem & Traveling Salesman Problem using Local Search
📌 Overview

This project is part of the Introduction to Artificial Intelligence course. The main objectives are to understand and implement AI problem-solving strategies using search and optimization techniques.

The tasks include:

N-Queen Problem – solving the classic constraint satisfaction problem.

Traveling Salesman Problem (TSP) – solving an NP-hard optimization problem using local search algorithms.

🧩 1. N-Queen Problem

The N-Queen Problem requires placing N queens on an N × N chessboard such that no two queens attack each other.

Key Concepts:

Constraint satisfaction problem (CSP)

Backtracking search

Heuristics (e.g., Minimum Conflicts)

Approach:

Implement a solver that finds a valid configuration of N queens.

Can be solved using:

Backtracking

Local search (Hill-Climbing, Simulated Annealing)

Example:
For N = 8, one valid solution is a placement where no queens share the same row, column, or diagonal.

🚗 2. Traveling Salesman Problem (TSP) with Local Search

The Traveling Salesman Problem (TSP) asks for the shortest possible route that visits each city exactly once and returns to the origin city.

Key Concepts:

Combinatorial optimization

Local search algorithms

Approximation instead of exact solution (since TSP is NP-hard)

Approach:

Represent cities as nodes and distances as edges.

Start with a random tour.

Improve the tour using local search techniques, such as:

Hill-Climbing

Simulated Annealing

Tabu Search

Goal:
Find a route with minimal travel cost (distance/time).

⚙️ Implementation Details

Language: Python / Java / C++ (depending on course requirements)

Input:

N-Queen → board size N.

TSP → number of cities and distance matrix.

Output:

N-Queen → one valid solution (or multiple if required).

TSP → optimized tour and total cost.

📖 Learning Outcomes

Understand constraint satisfaction and optimization in AI.

Learn to apply backtracking and local search strategies.

Explore trade-offs between exact and approximate solutions.

Gain practical experience solving NP-hard problems using heuristics.

👩‍💻 Authors

Student Name

Student ID

Course: Introduction to Artificial Intelligence

Institution: [Your University]
