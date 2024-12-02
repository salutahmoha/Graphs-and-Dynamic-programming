# Graphs
Graphs are a versatile and fundamental data structure used to represent a set of objects (nodes or vertices) connected by relationships (edges). They are widely used in computer science to model real-world systems such as social networks, transportation maps, communication networks, and more. Graphs can be classified based on their properties:

## Types of Graphs
### Directed vs. Undirected Graphs:

## Directed Graphs (Digraphs)
 Each edge has a direction, pointing from one vertex to another. The order of the vertices matters.
Example: In a road map, a one-way street is a directed edge.
## Undirected Graphs
 Edges have no direction, representing a mutual relationship between vertices. The order of the vertices does not matter.
Example: In a social network, a friendship is mutual, so it's an undirected edge.
## Weighted vs. Unweighted Graphs:

### Weighted Graphs:
 Each edge is assigned a weight or cost, often representing distance, time, or capacity.  
Example: A flight route map where edge weights represent ticket prices or distances.  
## Unweighted Graphs:
 Edges are treated equally with no weights assigned.  
Example: A friendship graph where each connection is uniform.
Graph Representations  
Graphs can be represented in various ways in memory:  

Adjacency Matrix: A 2D array where matrix[i][j] is 1 (or weight) if there is an edge between vertices i and j.  
Adjacency List: An array or list where each vertex stores a list of its neighbors. This is space-efficient for sparse graphs.  
Edge List: A simple list of edges where each edge is represented as a pair (or triplet for weighted graphs) of vertices.  


# Dynamic Programming (DP)
Dynamic Programming (DP) is a problem-solving paradigm used for optimization and decision-making. It is especially useful for problems where a solution can be composed of solutions to overlapping subproblems.

## Core Principles of DP
### Optimal Substructure:
 The solution to a problem can be constructed using solutions to its subproblems.  
Example: In finding the shortest path in a graph, the shortest path to a destination vertex depends on the shortest path to its neighbors.
Overlapping Subproblems: The problem can be broken down into subproblems that are solved multiple times.  
Example: In Fibonacci sequence calculation, the value of Fib(n) relies on Fib(n-1) and Fib(n-2).
DP Techniques  
### Top-Down Approach (Memoization):
Problems are solved recursively, and results of subproblems are stored (memoized) to avoid redundant computations.
Example: Recursive Fibonacci with memoization.
### Bottom-Up Approach (Tabulation):
Problems are solved iteratively starting from the smallest subproblem, and results are stored in a table to build the solution step-by-step.
Example: Iterative Fibonacci using an array to store values.
Applications of Dynamic Programming
## Optimization Problems:
1.Knapsack Problem: Maximizing the value of items that can fit in a knapsack of fixed capacity.  
2.Matrix Chain Multiplication: Finding the most efficient way to multiply a series of matrices.  
3.Sequence Problems:  
Longest Common Subsequence (LCS): Finding the longest subsequence common to two sequences.  
4.Longest Increasing Subsequence (LIS): Finding the longest subsequence where each element is larger than the previous one.  
5.Pathfinding in Graphs:  
Bellman-Ford Algorithm: Shortest paths in a graph with negative edge weights.    
6.Floyd-Warshall Algorithm: Finding shortest paths between all pairs of vertices.  
7.Game Theory Problems:  
Solving games like coin-picking or chess endgames.

## References
.Introduction to Graph Theory  
.Dynamic Programming  
.Dijkstra's Algorithm  
.Bellman-Ford Algorithm
