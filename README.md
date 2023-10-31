# 0x1D. C - Binary Tree Data Structures

## Description

This project explores the world of binary trees and their various types. Binary trees are fundamental data structures in computer science, offering efficient ways to organize, search, insert, and delete data. This project covers the implementation and usage of basic binary trees, Binary Search Trees (BSTs), AVL Trees, and Max Binary Heaps. It also provides insights into the differences between these tree types, their characteristics, and common traversal methods.

## Binary Tree Data Structures

```c
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;


At the end of this project, you will be able to:

- Explain what a binary tree is
- Differentiate between a binary tree and a Binary Search Tree (BST)
- Understand the potential time complexity benefits compared to linked lists
- Define the depth, height, and size of a binary tree
- Enumerate various traversal methods for navigating a binary tree
- Recognize different types of binary trees, including complete, full, perfect, and balanced binary trees.
