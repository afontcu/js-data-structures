# What's the difference between a binary search tree (BST) and a heap?

First of all: both a Heap and a BST are tree-based data structures.

Heap just guarantees that elements on higher levels are greater (for max-heap) 
or smaller (for min-heap) than elements on lower levels.

BST guarantees order (from "left" to "right"). If you want sorted elements, go with BST.


## What is a Heap better at?
Average time insertion into a binary heap is O(1), for BST is O(log(n)).

Heap is better at findMin/findMax: O(1). ([Caution with this](https://stackoverflow.com/questions/7878622/can-we-use-binary-search-tree-to-simulate-heap-operation).
It is easy to modify a BST to keep track of the largest/smallest element)


## What is a BST better at?
BST is good at all finds: O(log(n))


## What else?
Insert is O(log(n)) for both structures.


## When should I use one or another?
Priority-related searches (such as finding the min/max value): go with Heap.

If you want to maintain an order and use it to your advantage: go with BST.

