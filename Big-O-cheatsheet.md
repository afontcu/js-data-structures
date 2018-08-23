# Big-O Complexity Cheatsheet

There are *tons* of good resources out there about Big-O complexity and
data structures.

I just needed a quick cheatsheet as a reference, a simple place where I could
double check what's the worst case scenario regarding the Array deletion
complexity, for instance.


## The Cheatsheet

| Name                    | Access    | Search    | Insertion | Deletion  |
|-------------------------|----------:|----------:|----------:|----------:|
| Array                   | O(1)      | O(n)      | O(n)      | O(n)      |
| Stack                   | O(n)      | O(n)      | O(1)      | O(1)      |
| Queue                   | O(n)      | O(n)      | O(1)      | O(1)      |
| Singly-Linked List      | O(n)      | O(n)      | O(1)      | O(1)      |
| Doubly-Linked List      | O(n)      | O(n)      | O(1)      | O(1)      |
| Hash Table              | N/A       | O(n)      | O(n)      | O(n)      |

All these structures have a Space Complexity of O(n)

### Trees 
| Name                    | Access    | Search    | Insertion | Deletion  |
|-------------------------|----------:|----------:|----------:|----------:|
| Binary Search Tree      | O(n)      | O(n)      | O(n)      | O(n)      |
| B-Tree                  | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) |

All these structures have a Space Complexity of O(n)
