
# Tree
- Collection of nodes connected by edges
- Non-linear data structure like graph

## Terms
- Root Node
  - The topmost node of the tree
  - Contains data and pointers (or object references)
- Parent Node > Child Node
- Edge
  - The link between two nodes
- Sibilings
  - Child nodes wiht the same parent
- Leaf
  - Node with no children
- Height
  - The length of the longest path to a leaf
- Depth
  - The length of the path to its root

## Types
- Binary Tree
  - Tree with binary constraint
  - Max two child nodes from any given node
```
// Definition for a binary tree node.
function TreeNode(val, left, right) {
  this.val = (val===undefined ? 0 : val)
  this.left = (left===undefined ? null : left)
  this.right = (right===undefined ? null : right)
}
```
  
- Binary Search Tree (BST)
  - Also called ordered or sorted binary tree
  - With order constraint
    - Left node < parent node
    - Right node > parent node

## Tree Traversal
- Depth-First Search (DFS)
  - With Stack
  - Pre-order
    - Root, Left, and Right
    - FBADCEGIH
  - In-order
    - Left, Root, and Right
    - ABCDEFGHI
  - Post-order
    - Left, Right, and Root
    - ACEDBHIGF
  
- Breadth-First Search (BFS)
  - With Queue
  - Level by level
    - FBGADICEH
<img src="https://github.com/irnkwon/algorithm/blob/master/concepts/images/tree.png" width="300px" />

# References
- https://leetcode.com/explore/learn/card/data-structure-tree/
- https://www.freecodecamp.org/news/all-you-need-to-know-about-tree-data-structures-bceacb85490c/
