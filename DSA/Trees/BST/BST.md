# What is a Binary Search Tree (BST)?

A BST is a type of Tree data structure where children node values are sorted starting from the root, and sorted all the way down to the [leaves](../Leaves.md) of the tree.

Given a root of a BST with a value of 5, any values added to this tree would check the root value, if the newly added value is lower than the root value, they would be sent down the left side of the tree, and the process repeated. If the newly-added value is larger than the root, it would be sent down the right side and the process repeated. If there is no value when sent down either left or right from the parent node, a new node with that value will be added there.

Algorithm:
1. Create recursive function to add value:
1. Check parent node against new value.
1. If smaller, move root to root.left. If smaller move root to root.right. (but before we do ->) If root.left.value or root.right.value (wherever is being traversed next) is null, that means there is no node there, and we can create a new node with new value and set root.left or root.right (again, wherever the value is being sorted to) to the newly-created node.

[<-- Back to Trees](../Trees.md)