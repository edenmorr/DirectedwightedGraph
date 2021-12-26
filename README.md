# DirectedwightedGraph


## **project Explanation**
---
Written by eden mor and danielle musai.  
In this task we had to implement a data structure of a directed weighted directed graph 
In Python, the implementation includes the diGraph class as well as the GraphAlgo class. The center idea is to use the previous implementation of our previous task and show it in Python, then we needed to compere our solution performance for our previous implementation in Java.
---
### **the interfaces we needed to implement in the class GraphAlgo:**
* get_graph – returns the directed graph on which the algorithm works on.
* save_to_json – Saves the graph in JSON format to a file
* load_from_json – Loads a graph from a json file.
* shortest_path –  Returns the shortest path from node id1 to node id2 using Dijkstra's Algorithm
* TSP – Finds the shortest path that visits all the nodes in the list 
* centerPoint - Finds the node that has the shortest distance to it's farthest node.
* plot_graph -  Plots the graph.
---
### **the interfaces we needed to implement in the class diGraph:**
*v_size - Returns the number of vertices in this graph
*e_size - Returns the number of edges in this graph
*get_all_v - return a dictionary of all the nodes in the Graph, each node is represented using a pair
*all_in_edges_of_node- return a dictionary of all the nodes connected to (into) node_id
*all_out_edges_of_node- return a dictionary of all the nodes connected from node_id , each node is represented using a pair
*get_mc - Returns the current version of this graph, on every change in the graph state - the MC should be increased
* add_edge - Adds an edge to the graph.
* add_node -  Adds an node to the graph.
*remove_node-  Removes a node from the graph.
*remove_edge-  Removes an edge from the graph.
---
### **Links**
---
more infurmation about Dijkstra's algorithm:  
https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm
https://www.youtube.com/watch?v=pVfj6mxhdMw
---
## **the graph** ##
*The graph consists of nodes and edges  
the node has id, pos, edges-in and edges-out
---
### **the graph**
![graph](https://user-images.githubusercontent.com/93930203/147415745-2fe4c723-19f4-4b80-8682-93e6b615f062.jpeg)


