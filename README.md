# TDA_ABB
Binary Search Tree 

Is a node-based binary tree data structure which has the following properties:

The left subtree of a node contains only nodes with keys lesser than the node’s key.
The right subtree of a node contains only nodes with keys greater than the node’s key.
The left and right subtree each must also be a binary search tree.

**COMPILATION:**
```
gcc *.c -o abb -g -std=c99 -Wall -Wconversion -Wtype-limits -pedantic -Werror -O0

./abb

valgrind --leak-check=full --track-origins=yes --show-reachable=yes ./abb
```
