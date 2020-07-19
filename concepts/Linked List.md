
# Linked List
- Dynamic array
  - Static array = fixed array = array
- Collection of data elements, called nodes
  - Contains reference to the next node in the list
- No indexing

## Types
- Singly Linked List
  - Uni-directional
  - A node in a singly linked list has the value field, and a "next" reference field to link nodes sequentially

<img src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/04/12/screen-shot-2018-04-12-at-152754.png" width="500px" />

```
// Definition for singly-linked list.
function ListNode(val, next) {
  this.val = (val===undefined ? 0 : val)
  this.next = (next===undefined ? null : next)
}
```

- Doubly Linked List
  - Bi-directional
  - Has one more reference field which is known as the "prev" field. You are able to know the previous node of the current node with this extra field
  
<img src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/04/17/screen-shot-2018-04-17-at-161130.png" width="500px" />

```
// Definition for doubly-linked list.
function ListNode(val, next, prev) {
  this.val = (val===undefined ? 0 : val)
  this.next = (next===undefined ? null : next)
  this.prev = (prev===undefined? null : prev)
}
```
  
# Reference
- https://leetcode.com/explore/learn/card/linked-list/
