# Trees

**Trees** are a non-linear data structure as it dosen't store in a sequential order, it takes a hierarchical structure.

There are two kinds of trees:
    
   1.  **Binary trees**: these can have only two children per parent
   2.  **K-ary Trees**: these canhave more than two children per parent

|**Term**|**Meaning**|
|--------|-----------|
|*Node*|Tree node is container that stores a value and a pointer to another node in the tree|
|*Root*|The first node in the tree|
|*K*|A value that specifies the allowed number of children for each node, K is 2 in a binary tree|
|*Left*|The reference to a child node in a binary tree|
|*Right*|The reference to a child node in a binary tree|
|*Edge*|The parent-child link|
|*leaf*|Node without any children|
|*Height*|The number of efges from the root to the last leaf|

![tree](https://miro.medium.com/max/975/1*PWJiwTxRdQy8A_Y0hAv5Eg.png)

## Traversing Trees

There are two main ways:

1. **Depth First**.
2. **Breadth First**

### Depth First

This method prioritizes traversing the depth (height), and that can be done in a couple of ways:

- **Pre-order**: root --> left --> right
- **In-ordder**: left --> root --> right
- **Post-order**: left --> right --> root

> most commen way of traversing a tree data structure while using depth first method is **recursion**

### Breadth First

This method prioritizes traversing the tree level by level.

- When using the breadth first method we traverse using a queue
- The enqueuing order is from left to right.

## Big O:

- The time complexity of most of the operations will be a `O(n)` as it will involve going through the entire tree.

- The space complexity of breadth first insertion is `O(w)`, where `w` is the largest width in the tree.

- The time complexity for depth first would be `O(log n)`.

## Binary Search Trees

They are a kind of trees where all the nodes on the left of the root are smaller than it, and all the nodes on the right are larger than it.

- This kind of tree is great for searching as it allows finding the value by looking if it's smaller or larger than the root and going from there.
- The time complexity is usually `O(log n)`, but in the worst casses it's `O(n)`
- The space complexity is `O(1)`
