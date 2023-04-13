# Data Structures and Algorithms

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
      Data Structures are a specialized means of organizing and storing data in computers in such a way that we can perform operations on the stored data         more efficiently. Data structures have a wide and diverse scope of usage across the fields of Computer Science and Software Engineering.

      Below are 8 common data structures:
      
      1. Arrays: An array is a structure of fixed-size, which can hold items of the same data type. It can be an array of integers, an array of floating-            point numbers, an array of strings or even an array of arrays (such as 2-dimensional arrays). Arrays are indexed, meaning that random access is            possible.

         Array operations:
         * Traverse: Go through the elements and print them.
         * Search: Search for an element in the array. You can search the element by its value or its index
         * Update: Update the value of an existing element at a given index

         Inserting elements to an array and deleting elements from an array cannot be done straight away as arrays are fixed in size. If you want to                insert an element to an array, first you will have to create a new array with increased size (current size + 1), copy the existing elements and            add the new element. The same goes for the deletion with a new array of reduced size.

         Applications of arrays:
         Used as the building blocks to build other data structures such as array lists, heaps, hash tables, vectors and matrices.
         Used for different sorting algorithms such as insertion sort, quick sort, bubble sort and merge sort.

      2. Linked Lists: A linked list is a sequential structure that consists of a sequence of items in linear order which are linked to each other. Hence, you have to access data sequentially and random access is not possible. Linked lists provide a simple and flexible representation of dynamic sets.

            Elements in a linked list are known as nodes.

            Each node contains a key and a pointer to its successor node, known as next.

            The attribute named head points to the first element of the linked list.

            The last element of the linked list is known as the tail.

            Following are the various types of linked lists available.

            Singly linked list — Traversal of items can be done in the forward direction only.
            Doubly linked list — Traversal of items can be done in both forward and backward directions. Nodes consist of an additional pointer known as prev, pointing to the previous node.
            Circular linked lists — Linked lists where the prev pointer of the head points to the tail and the next pointer of the tail points to the head.
            Linked list operations
            Search: Find the first element with the key k in the given linked list by a simple linear search and returns a pointer to this element
            Insert: Insert a key to the linked list. An insertion can be done in 3 different ways; insert at the beginning of the list, insert at the end of the list and insert in the middle of the list.
            Delete: Removes an element x from a given linked list. You cannot delete a node by a single step. A deletion can be done in 3 different ways; delete from the beginning of the list, delete from the end of the list and delete from the middle of the list.
            Applications of linked lists
            Used for symbol table management in compiler design.
            Used in switching between programs using Alt + Tab (implemented using Circular Linked List).







2. How can we ensure that we’ll avoid an infinite recursive call stack?
