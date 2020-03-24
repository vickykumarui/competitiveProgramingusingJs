Graph : A data structure consists of finite(and possibly mutable) set of vertices or node or points together with a set of unordered
pair of set of vertices for a undirected graph or a set of ordered pair for directed graph

Graph = node + connections

Graph uses
Location/map
Routing algorithm
Social networks
Recommendation like in netflix people also watch in amazon - Frequently bought with

Tree is also a graph with restriction that there is oly one path to reach from any vertices to another

Types of graph:

Undirected graph - There is no direction on edges(connection) between two node/vertices
Directed graph - There is direction on edges(connection)
Weighted graph -  when there is weight assigned to graph

Storing graphs - There are two common ways to store graphs

1. Adjacency Matrics -  takes more space, Slower to iterate over all edges, Faster to look up specific edge


Example: We maintain a 2D array M*M where we have each value 
2. Adjacency List
We keep it in object(hash) Can take less space, Faster to iterate over all edges, can be slower to look up specific edge
