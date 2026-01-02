# Concpet
A linked list is another data structure that is like an array in the sense that it stores elements in an ordered sequence. But there are also some key differences.

The main difference is that linked lists are made up of objects called `ListNode`'s. This object contains two attributes:
- `value` - This stores the value of the node. It could be a character, an integer, etc.
- `next` - This stores the reference to the next node in the linked list.
- # Variation
	- ### Singe linked list
	  Each node has one pointer
	- Python code example
	  ```
	  class node:
	      def __init__(val=None, next=None):
	          self.val = val
	          self.next = next
	  ```
	- ### Doubly Linked Lists
	  Each node now has two pointers. In addition to the `next` pointer, we have a `prev` pointer which points to the previous node. If the `prev` pointer points to `null`, it is an indication that we are at the head of the linked list.
	- Python code example
	  ```
	  class node:
	      def __init__(val=None, next=None, prev=None):
	          self.val = val
	          self.next = next
	          self.prev = prev
	  ```
-