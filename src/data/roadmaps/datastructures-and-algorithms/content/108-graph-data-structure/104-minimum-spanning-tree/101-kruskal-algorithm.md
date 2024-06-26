# Kruskal's Algorithm

Kruskal's algorithm is a popular procedure in computer science for finding minimum spanning trees in a graph, developed by Joseph Kruskal in 1956. The algorithm operates by sorting the edges of the graph by their weight in ascending order. Then, it loops through each, adding the edge to the spanning tree if it doesn't form a circuit with the edges already there. This process repeats until all the vertices in the graph are included in the tree. Kruskal's algorithm belongs to the group of Greedy Algorithms as it tries to find the local optimum at each stage with the hope of finding the global optimum. It has an overall time complexity of O(E log E) or O(E log V), where E is the number of edges and V is the number of vertices.


Visit the following resources to learn more:

- [Kruskals Algorithm in 2 Minutes](https://www.youtube.com/watch?v=71UQH7Pr9kU)
- [Graph Algorithms II - DFS, BFS, Kruskals Algorithm, Union Find Data Structure - Lecture 7](https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
