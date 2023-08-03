*BINARY TREE.*
A binary tree is a type of data structure composed of nodes, where each node has at most two children, referred to as left child and right child. The topmost node of the tree is called the root.
*General*
What is a binary tree
What is the difference between a binary tree and a Binary Search Tree
What is the possible gain in terms of time complexity compared to linked lists
What are the depth, the height, the size of a binary tree
What are the different traversal methods to go through a binary tree
What is a complete, a full, a perfect, a balanced binary tree
Data structures
Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

Basic Binary Tree
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
Binary Search Tree
typedef struct binary_tree_s bst_t;
AVL Tree
typedef struct binary_tree_s avl_t;
Max Binary Heap
typedef struct binary_tree_s heap_t;
Note: For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.

Print function
To match the examples in the tasks, you are given this function

This function is used only for visualization purposes.
-  a function that deletes an entire binary tree
- a function that checks if a node is a leaf


- a function that checks if a given node is a root
- function that goes through a binary tree using pre-order traversal
-  function that goes through a binary tree using in-order traversal
- function that goes through a binary tree using post-order traversal
- function that measures the height of a binary tree
- function that measures the depth of a node in a binary tree
-  function that measures the size of a binary tree
- function that counts the leaves in a binary tree
- function that counts the nodes with at least 1 child in a binary tree
- a function that measures the balance factor of a binary tree
- function that checks if a binary tree is full
- function that checks if a binary tree is perfect
- function that finds the sibling of a node


 
