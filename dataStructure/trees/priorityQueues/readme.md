PriorityQueue is datastructure where each element has priority. Elements with higher priority is served before elements with lower priority

Prioriy Queue can be implemented with array where to get highest priority element we will fetch it from array, problem with this approach 
is that everytime we fetch element it will be of O(n)

hence to implement PriorityQueue we use maxHeap or meanHeap in which node is always max or min respecttively so taking out priority element
is always O(1)
