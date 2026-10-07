MST 
---
Prims ALGORITHM 

Prim’s Algorithm
------------------------
1. Start with any vertex.
2. Mark the selected vertex as visited.
3. Find the minimum-weight edge connecting a visited vertex to an unvisited vertex.
4. Add that edge to the MST.
5. Mark the newly selected vertex as visited.
6. Repeat steps 3–5 until all vertices are included.
7. Display the selected edges and total MST cost.


              START
                |
                v
        Choose starting vertex
                |
                v
      Find smallest connected edge
                |
                v
          Add edge to MST
                |
                v
          Add new vertex
                |
                v
      Are all vertices included?
          /             \
        NO               YES
        |                 |
        v                 v
 Find next smallest      STOP
 connected edge
