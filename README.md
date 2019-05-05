# Minimum Cost Spanning Tree
Algorithmic implementation to find Minimum Spanning Tree

__Complete graph__ `G` is simple graph in which any two vertices are joined by an `edge`. A complete graph of `n` vertices will have `n(n-1)/2` edges.

__Spanning tree__ `H` is an acyclic graph whose length of `V(H) = V(G)` and `E(H)` is subset of `E(G)`, where `G` is any given graph.

Now if we assign weights (certain integer) to edges of graph `G` then `G` becomes a weighted graph. This opens to certain problems or ideas to find __`minimum cost spanning tree`__ of graph `G`.

To find minimum cost spanning tree, we implement different algorithms such as,

* __`Kruskal's Algorithm`__
* __`Prim's Algorithm`__
