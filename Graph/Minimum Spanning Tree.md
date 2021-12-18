# • Minimum Sapnning Tree

A Graph is represented as

      G(V,E)  here  V = number of vertex/node
                    E = number of Edges
                       
Spanning Tree of G is :

      G'(V',E')  here     V' = V   i.e it will contain same number of verties as main Grapg    
                          E' = (V-1) or subsets of E
                          
                          
### 	A Spanning tree with least total cost is called Minimum Spanning Tree. It will never contain any Cycle.
     


There are two Algorithms for finding minimum Spaning Tree :

                                                         i. Kruskal's Algorithm
                                                        ii. Prim's Algorithm
                                                        

## • Kruskal's Algorithm :
1.	Erase all the Parallel(keeping the least costed edge) and Loop edges from the Graph.
2.	Make a Sorted list of all the Edges according to their Edge Weights. (Increasing Order)
3.	Draw the edges or connect the nodes from beginning of the Sorted list keeping in mind that NO CYCLE is being created.


## • Prim's Algorithm :
1.	Erase all the Parallel(keeping the least costed edge) and Loop edges from the Graph.
2.	Choose any arbitrary node as root node to start traversing.
3.	Check all the Adjacent or Outgoing edge's for ALL SELECTED/VISITED nodes and chose the least costed unvisited edge.
