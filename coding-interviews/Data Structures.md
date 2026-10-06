### Array
Array - ordered collection of data (from the same type usually)
Easy to find elements as they all have an index

In memory can be stored next to each other.
Time complexity
Read O(1)
Insert/ Delete O(n)


### Linked List

Each element has a pointer (the address of the next element of the list)
No index which is why search is long as we need to keep seeing where the pointer is
Pointers used to find the next element.

In memory can be stored anywhere. 

Insertion - get the previous pointer to point to it
Deletion - get the previous pointer to point to the one ahead
Time complexity
Read O(n)
Insert/ Delete O(1)


### Hashmaps

(Hash tables, dictionaries)

Unordered
Key: Value

Read/ Insert/ Delete O(1)


### Stacks
Last in, first out

Time complexity
Push (Add), Pop (Remove), Peek (Look) O(1)


### Queues
First in, first out

Time complexity
Add - Enqueue - O(1)
Front is gone - Dequeue - O(1)
Front - O(1)



### Trees
Parent and child
Nodes and leaves

Binary Tree - up to two children
Binary Search Tree - left side < parent, right side > parents

Time complexity
O(logn)


### Graphs