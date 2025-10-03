README: Experimental Profiling & Visualization of Algorithms
Overview

This project profiles and visualizes the performance of four algorithmic problems:

Job Sequencing (Greedy)

0/1 Knapsack (Dynamic Programming)

Sudoku Solver (Backtracking)

Password Cracking (Brute-Force)

Performance is analyzed in terms of time taken, memory usage, and, for recursive algorithms, stack usage.

Profiling Tools

time module for measuring execution time.

memory_profiler for memory usage.

Custom recursion depth tracker for backtracking problems.

Experiments & Findings
1. Job Sequencing

Time complexity: O(n log n) due to sorting.

Memory: Linear with input size.

Visualization: Time vs number of ads.

2. Knapsack (DP)

Time & Memory: O(n × budget).

Visualization: Time and memory vs budget.

3. Sudoku Solver

Time complexity: Exponential in blanks.

Stack usage: Proportional to recursion depth.

Visualization: Time, memory, recursion depth vs blanks.

4. Password Cracking

Time complexity: O(|charset|^L), exponential growth.

Memory: Low, generated on the fly.

Visualization: Time vs password length, attempts vs length.
