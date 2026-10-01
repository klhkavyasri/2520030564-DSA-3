# 2520030564-DSA-3
Dynamic Programming
Responsibility

Member 2 is responsible for implementing the main Dynamic Programming algorithm used to calculate the minimum multiplication cost.

Tasks Completed
Created the DP cost table.
Implemented the Matrix Chain Multiplication recurrence.
Evaluated all possible split positions.
Selected the minimum multiplication cost.
Stored solutions for smaller subproblems.
Analyzed the algorithm complexity.
Recurrence

m[i][j] = min(m[i][k] + m[k+1][j] + p[i-1] * p[k] * p[j])

Concepts Covered
Dynamic Programming
Optimal substructure
Overlapping subproblems
Recurrence relation
Bottom-up computation
Cost table
Complexity

Time Complexity: O(n³)

Space Complexity: O(n²)

Contribution

The Dynamic Programming module is responsible for efficiently finding the minimum number of scalar multiplications required to multiply the complete matrix chain.
