This is a recursive DFS, for very large or deeply nested graphs.
The logic use in is, if node has not been visited yet it will print it and will mark visited.
its recurse into each neighbour, also backtrack when no unvisited neighbours remains.

A -> visit (first neighbour) go to B  
B -> visit go to D
D -> visit (no neighbour)(backtrack)go to E 
E -> visit go to F
F -> visit (no neighbour)(backtrack)go to C
C -> visit go to F(already visited)(skip)
