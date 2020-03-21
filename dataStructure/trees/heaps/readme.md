Binary Heap is also like binar tree with rule that

Each parent has atmost two children

In maxbinaryheap parent node are always larger than child nodes but there is not gurantee between siblings

In minbinaryheap parent node are always smaller than child nodes

Binary heap is as compact as possible, all children of each node are filled, first left child is filled

Binary Heap implementation with array.

We will maintain an array for tree

Important point to Note: In heap we always keep it compact so we always fill left child first than right child

If position of node is n than its child will be at 2n+1(left child) 2n+2(right child)

If position of node in n than parent is at index (n-1)/2 - floored i.e Math.floor((n-1)/2)
