
# Trees
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
- <strong>Binary Tree</strong> vs Tree
  - Tree with binary constraint
  - Max two child nodes from any given node
  - Ternary Tree has at most three child nodes
```
// Definition for a binary tree node.
function TreeNode(val, left, right) {
  this.val = (val===undefined ? 0 : val)
  this.left = (left===undefined ? null : left)
  this.right = (right===undefined ? null : right)
}
```

- <strong>Binary Search Tree (BST)</strong> vs Binary Tree
  - Also called ordered or sorted binary tree
  - With order constraint
    - Left node < parent node
    - Right node > parent node

- <strong>Balanced Tree</strong> vs Unbalanced Tree
  - Not terribly imbalanced tree
  - ≠ Perfect binary tree
  - Two common types
    - Red-black trees and AVL trees

- Complete Binary Tree
  - All levels are fully filled except possibly the lowest one, which is filled left to right

- Full Binary Tree
  - Every node has either zero or two children

- Perfect Binary Tree
  - Both full and complete
  - All leaf nodes are on the level that has the maximum number of nodes
  - Must have exactly 2^l - 1 nodes, where l is the number of levels

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
- https://www.amazon.ca/Cracking-Coding-Interview-Programming-Questions/dp/0984782850
