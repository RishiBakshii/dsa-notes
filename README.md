## what are trees
![](https://www.tutorialride.com/images/data-structures/structure-of-tree.jpeg)
- hierarchical data structure
- most powerful and advanced data structures.
- non-linear data structure compared to arrays, linked lists, stack and queue.
- nodes connected by edges.
- Tree is a collection of elements called Nodes, where each node can have arbitrary number of children
- Tree is a collection of elements called Nodes, where each node can have arbitrary number of children. 


## Levels of a node
- Levels of a node represents the number of connections between the node and the root. It represents generation of a node. If the root node is at level 0, its next node is at level 1, its grand child is at level 2 and so on. Levels of a node can be shown as follows
![](https://www.tutorialride.com/images/data-structures/levels-of-tree.jpeg)

## Binary Tree Traversal
- Binary tree traversing is a process of accessing every node of the tree and exactly once. A tree is defined in a recursive manner. Binary tree traversal also defined recursively. 

## here are three techniques of traversal:
- Preorder Traversal
	![](https://www.tutorialride.com/images/data-structures/preorder-traversal.jpeg)
	- Step 1 : Start from the Root.
	- Step 2 : Then, go to the Left Subtree.
	- Step 3 : Then, go to the Right Subtree.

- Postorder Traversal
- Inorder Traversal


## Binary Tree
![](https://www.tutorialride.com/images/data-structures/binary-tree.jpeg)
- maximum 2 children
- It is a method of placing and locating the records in a database
- data store in (RAM)

## Representation of Binary Tree using Array
![](https://www.tutorialride.com/images/data-structures/binary-tree-using-array.jpeg)

- Array index is a value in tree nodes and array value gives to the parent node of that particular index or node. Value of the root node index is always -1 as there is no parent for root. When the data item of the tree is sorted in an array, the number appearing against the node will work as indexes of the node in an array.

![](https://www.tutorialride.com/images/data-structures/location-number-array-tree.jpeg)

## Binary Search Tree
- special property called BST
- each child or siblings sotre their parent pointers
- key defines a key which is stored at the node.
- Binary Search Tree is a binary tree where each node contains only smaller values in its left subtree and only larger values in its right subtree
![](https://www.tutorialride.com/images/data-structures/binary-search-tree.jpeg)
- it is used to enchance the performance of binary tree
- It focuses on the search operation in binary tree.
- Every binary search tree is a binary tree, but all the binary trees need not to be binary search trees.

## Binary Search Tree Operations
- ### Insert Operation
	- Insert operation is performed with O(log n) time complexity in a binary search tree.
	- Insert operation starts from the root node. It is used whenever an element is to be inserted.
![](https://www.tutorialride.com/images/data-structures/insert-operation.jpeg)

	- The following algorithm shows the insert operation in binary search tree:
	- Step 1: Create a new node with a value and set its left and right to NULL. 

- Step 2: Check whether the tree is empty or not. 

- Step 3: If the tree is empty, set the root to a new node. 

- Step 4: If the tree is not empty, check whether a value of new node is smaller or larger than the node (here it is a root node).

- Step 5: If a new node is smaller than or equal to the node, move to its left child. 

- Step 6: If a new node is larger than the node, move to its right child. 

- Step 7: Repeat the process until we reach to a leaf node.

## Search Operation
- Search operation is performed with O(log n) time complexity in a binary search tree.
- This operation starts from the root node. It is used whenever an element is to be searched.
- The following algorithm shows the search operation in binary search tree:
- Step 1: Read the element from the user .

- Step 2: Compare this element with the value of root node in a tree. 

- Step 3: If element and value are matching, display “Node is Found” and terminate the function. 

- Step 4: If element and value are not matching, check whether an element is smaller or larger than a node value. 

- Step 5: If an element is smaller, continue the search operation in left subtree. 

- Step 6: If an element is larger, continue the search operation in right subtree.

- Step 7: Repeat the same process until we found the exact element. 

- Step 8: If an element with search value is found, display “Element is found” and terminate the function. 

- Step 9: If we reach to a leaf node and the search value is not match to a leaf node, display “Element is not found” and terminate the function.

## There are 4 types of binary tree:
	- Full Binary Tree
	- Complete Binary Tree
	- Skewed Binary Tree
	- Extended Binary Tree
![](https://bcastudyguide.files.wordpress.com/2020/07/img_20200720_091915.jpg)
![](https://bcastudyguide.files.wordpress.com/2020/07/img_20200720_091957.jpg)
![](https://bcastudyguide.files.wordpress.com/2020/07/img_20200720_091939.jpg)
![](https://bcastudyguide.files.wordpress.com/2020/07/img_20200720_091925.jpg)


 
