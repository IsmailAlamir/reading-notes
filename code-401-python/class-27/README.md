# Graphs

### Definition:

A graph is a data structure that consists of a set of vertices (or nodes) and a set of edges that connect the vertices. The vertices represent the entities in the problem domain, and the edges represent the relationships between the vertices.

Graphs can be used to model a wide variety of problems, including social networks, transportation networks, and computer networks. They are often used to represent and solve problems in computer science and other fields, such as graph search algorithms, network flow, and optimization.

Graphs can be represented in a number of different ways, such as adjacency lists, adjacency matrices, and edge lists. The choice of representation often depends on the specific problem and the operations that will be performed on the graph.

Overall, the graph is a powerful and versatile data structure that can be used to model and solve many real-world problems.




**Some terminologies:**

| Term | Meaning |
|------|---------|
| Vertex | these are the nodes, and they can connect to zero or more nodes |
| Edge | connecting line between two nodes |
| Neighbor | a neighbor of a node is the node that is connected to it |
| Degree | a degree of a vertex is the number of edges connected to that vertex |

**Traversal techniques are**:
- *Breadth First*
- *Depth First*

### Kinds of graphs:

- **Undirected Graphs**: These kinds of graphs take a shape without a direction, meaning that they are connected without rule on how to be traversed.

- **Directed Graphs (Digraph)**: These kinds of graphs always move in a specific direction, meaning that they can traversed in a specific way and only in that way.

- **Complete Graphs**: A graph is a complete graph when all it's nodes are connected with each other.

- **Connected Graphs**: A graph is a connected graph when all it's nodes are connected with at least one edge.

- **Disconnected Graphs**: A graph is a disconnected graph when there are some nodes that don't have edges.

- **Acyclic Graph**: this kind of graph does not have any cycles within it, which means unlike undirected and directed graphs, nodes don't end up back at itself.


- **Cyclic Graphs**: this kind of graph starts and ends at the same point, completing a full circle.

### Graph Representation Techniques:

- **Adjacency Matrix**: this representation results in a binary 2d array, connections are represented using **ones**, and no connection is **zero**.

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjMatrix.PNG)

**Notes**:

1. The size of this representation is **n*n**.
2. Few connections within a representation is called a **spase graph**.
3. Many connections within a representation is called a **dense graph**.

- **Adjacency List**: this representation uses a linked list representation of all the connected nodes.

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjList.PNG)

