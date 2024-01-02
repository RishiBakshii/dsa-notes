## Stacks
- A stack is a container of objects that are inserted and removed according to the last-in first-out (LIFO) principle. In the pushdown stacks only two operations are allowed: push the item into the stack, and pop the item out of the stack. A stack is a limited access data structure – elements can be added and removed from the stack only at the top. push adds an item to the top of the stack, pop removes the item from the top. A helpful analogy is to think of a stack of books; you can remove only the top book, also you can add a new book on the top.
- the data type stack is an adapter class
- he underlying structure for a stack could be an array ,vector, an ArrayList, a linked list, or any other collection.
- all stack operations must run in constant time O(1)


A stack is a recursive data structure.

## Applications
-  reverse a word
- “undo” mechanism in text editors;
- Backtracking : this is a process when you need to access the most recent data element in a series of elements
- compiler’s syntax check for matching braces is implemented by using stack.

## Array-based implementation
- array (>=1) and top element refers to the capacity of the array size.
- when top = -1 ( stack is empty)
- and the stack is full when top = capacity-1
- In fixed-size static when top reaches capacity, the stack object throws an exception
- In a dynamic stack abstraction when top reaches capacity, we double up the stack size

## Linked List-based implementation
- best from the effecient point of view

## Queues
- a linear collection
- constant time O(1).
- first-in first-out (FIFO) principle
- enqueue(Enqueue means to insert an item into the back ) and 
- dequeue (means removing the front item)

## Circular Queue
![](https://cdn.programiz.com/sites/tutorial2program/files/circular-queue-program.png)
- Given an array A of a default size (≥ 1) with two references back and front, originally set to -1 and 0 respectively. Each time we insert (enqueue) a new item, we increase the back index; when we remove (dequeue) an item – we increase the front index.

