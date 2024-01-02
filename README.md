## Linked List
- A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image
![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)

- In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list

## Why Linked List?
Arrays is good for linear data of similar types, but arrays have the following limitations.

- 1) The size of the arrays is fixed: So we must know the upper limit on the number of elements in advance. Also, generally, the allocated memory is equal to the upper limit irrespective of the usage.

- 2) Inserting a new element in an array of elements is expensive because the room has to be created for the new elements and to create room existing elements have to be shifted.

## Advantages over array
- Dynamic size
- Ease of insertion/deletion

##  Drawbacks of linkedList
- Random acces is not allowed [sequential access]
- in each node extra space for pointer variable is required
- Not cache friendly, as not contiously stored 

## Linked List Representation
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list.jpg)
-Each node carries a data field(s) and a link field called next.
- Each node is linked with its next link using its next link.
- Last node carries a link as null to mark the end of the list.

## Types of linked List
- Simple Linked List
- Doubly Linked List 
- Circular Linked List 

## Basic operations by a linked list
- Insertion -Adds an element at the beginning of the list.
- Deletion - Deletes an element at the beginning of the list.
- Display - Displays the complete list.
- Search - Searches an element using the given key.
- Delete - Deletes an element using the given key.

## Insertion Operation
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_insertion_0.jpg)
- NewNode.next −> RightNode;
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_insertion_1.jpg)
- LeftNode.next −> NewNode;
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_insertion_2.jpg)
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_insertion_3.jpg)

## Deletion Operation
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_deletion_0.jpg)
- LeftNode.next −> TargetNode.next;
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_deletion_1.jpg)
- TargetNode.next −> NULL;
![](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list_deletion_2.jpg)
- We need to use the deleted node. We can keep that in memory otherwise we can simply deallocate memory and wipe off the target node completely.

## Doubly Linked List
![](https://www.tutorialspoint.com/data_structures_algorithms/images/doubly_linked_list.jpg)

- Link − Each link of a linked list can store a data called an element.
- Next − Each link of a linked list contains a link to the next link called Next.
- Prev − Each link of a linked list contains a link to the previous link called Prev.
- LinkedList − A Linked List contains the connection link to the first link called First and to the last link called Last.

## Circular Linked List
- Circular Linked List is a variation of Linked list in which the first element points to the last element and the last element points to the first element. Both Singly Linked List and Doubly Linked List can be made into a circular linked list.

## Singly Linked List as Circular
In singly linked list, the next pointer of the last node points to the first node.
![](https://www.tutorialspoint.com/data_structures_algorithms/images/singly_circular_linked_list.jpg)

## Doubly Linked List as Circular
- In doubly linked list, the next pointer of the last node points to the first node and the previous pointer of the first node points to the last node making the circular in both directions.
![](https://www.tutorialspoint.com/data_structures_algorithms/images/doubly_circular_linked_list.jpg)

## Header Linked List in C
- A header node is a special node that is found at the beginning of the list
- for example the length of the items in a list can be stored  in teh header node.

## Types of Header Linked List

### Grounded Header Linked List
![](https://media-geeksforgeeks-org.cdn.ampproject.org/i/s/media.geeksforgeeks.org/wp-content/uploads/20191110220324/GroundedList1.jpg)
- It is a list whose last node contains the NULL pointer. In the header linked list the start pointer always points to the header node. start -> next = NULL indicates that the grounded header linked list is empty. The operations that are possible on this type of linked list are Insertion, Deletion, and Traversing.

### Circular Header Linked List
![](https://media-geeksforgeeks-org.cdn.ampproject.org/i/s/media.geeksforgeeks.org/wp-content/uploads/20191110220322/CircularList.jpg)
- A list in which last node points back to the header node is called circular linked list. The chains do not indicate first or last nodes. In this case, external pointers provide a frame of reference because last node of a circular linked list does not contain the NULL pointer. The possible operations on this type of linked list are Insertion, Deletion and Traversing.



