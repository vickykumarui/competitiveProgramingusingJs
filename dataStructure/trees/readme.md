Tree is datastructure consists of node in a parent child relationship

Tree is non linear datastructure unlike linked list which is linear

Tree has only one root and all the nodes point to its children

Terminologies

Root: The top node in the tree

Child node: Node directly connected to another node when moving down from root

Parent node: Converse notion of child

Sibblings: Group of node with same parents

Leaf: A node with no children

Edge: connection between one node to another

Tree Application

HTML Dom, Folders in Operating System, JSON is tree structure

Commonly Used tree is binary tree

Binary tree : It has restriction that each node can have maximum 2 children

Binary Search Tree : It is special case of binary tree where restriction is that every node which is less than parent is always to left of it and node which is more than parent is to right 

Tree traversal

1. Breadth first search(BFS)

---------->10
 ------>6---->15
 --->3   8       20
 
 BFS - [10 6 15 3 8 20]
 
 2. Depth first search(DFS)
    a. In order (root lies in middle)
    b. Pre order (root lies in pre)
    c. Post order (root lies at end)
    
  Which one to choose BFS or DFS
  
  Time complexity of DFS and BFS are same as we visit every node once 
  
  Difference is in space complexity.
  
  In  BFS we keep in queue all the node at particular level and in DFS we recursivelly  call function till we reach end of node(depth) hence keeping reference of each node in dapth. So if width of tree is more use DFS and if height is more use BFS
  
