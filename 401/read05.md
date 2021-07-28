# Reading 05

## linked Lists

- Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

## Linear data structures

If we really want to understand the basics of linked lists, it’s important that we talk about what type of data structure they are. One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed. Linear structures, however, are the opposite of non-linear structures. In non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.

## Traversal

- When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing.

## Adding a Node

-Inserting element in the linked list involves reassigning the pointers from the existing nodes to the newly inserted node. Depending on whether the new data element is getting inserted at the beginning or at the middle or at the end of the linked list, we have the below scenarios.

- linked lists types are:
  - Singly linked lists which have a single track
  - doubly linked list the single track can be reversed
  - circular linked list where node that acts as the tail of the list so the node after the tail node becomes list start
