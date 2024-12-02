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
