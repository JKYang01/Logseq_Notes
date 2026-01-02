## Concept

Similar to [[linked lists]] , **binary trees** are another data structure that involve nodes and pointers.

With linked lists, we connected nodes in a straight line with `next` and `prev` pointers. Nodes in a binary tree also have at most two pointers, but we call them the **left child** and the **right child** pointers. The first node in a binary tree is referred to as the **root** node. We draw the pointers down instead of a straight line.

The value of a node can be any data type. A `TreeNode` class would look like the following. Notice how much of the implementation is similar to a `ListNode` discussed in the linked list chapter, except these nodes are considered **children**.
	- Python code
	  
	  ```class TreeNode:
	      def __init__(self, val):
	          self.val = val
	          self.left = None
	          self.right = None
	  ```