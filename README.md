# binary_search_trees
Practicing Binary Search Trees in JS.

O (log n) for searching and adding while they are balanced. If you have one long branch, then it’s basically a linked list. Good for storing dictionaries, phone books, storing users by userID, etc.

Depth-first Traversal:    
1. In-order => Touches smallest to largest numbers. Starts at bottom left and works up each branch.  
2. Pre-Order => Touches current node, then left children, then right children of each node. Useful for copying a Binary Search Tree.  
3. Post-Order => Touches all lower levels of a root first (left lower then right lower). Useful for safely deleting nodes without accidentally deleting parent nodes.

Breadth-first Traversal:  
Proceses all nodes on each level, level-by-level. Useful for example, defining a hierarchy of a corporation.
