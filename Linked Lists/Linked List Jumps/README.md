## Problem Statement : 
You are given a singly linked list node containing positive integers. Return the same linked list where every node's next points to the node val nodes ahead. If there's no such node, next should point to null.

**Constraints :**
n ≤ 100,000 where n is the number of nodes in node

### Example 1

**Input :**
node = 2 -> 1 -> 4 -> 1

**Output :**
2 -> 4

**Explanation :**
Note that 2's next is 2 node ahead. 4's next is out of bounds, so it's set to null.