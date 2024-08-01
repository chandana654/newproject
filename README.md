Basic Social Network Analysis Tool
Overview
This project is a basic social network analysis tool implemented in Python. It focuses on graph representation, degree centrality calculation, and basic visualization.

Features
Directed Graph Creation: Represents the network as a directed graph.
Node Addition: Adds nodes to the graph.
Edge Addition: Adds directed edges between nodes.
Centrality Calculations:
In-Degree Centrality: Measures the number of edges pointing to a node.
Out-Degree Centrality: Measures the number of edges pointing from a node.
Total Degree Centrality: Measures the total number of edges connected to a node (undirected).
Explanation
This project calculates and prints the centrality measures of a directed graph. Centrality measures indicate the importance of nodes in a graph.

Steps:
Directed Graph Creation: A new directed graph is created using NetworkX.
Node Addition: Four nodes - "chandana", "venky", "sreeram", and "sushma" - are added to the graph.
Edge Addition: Five directed edges are added between the nodes:
"chandana" to "venky"
"venky" to "sreeram"
"sreeram" to "sushma"
"sushma" to "chandana"
"venky" to "chandana"
In-Degree Centrality Calculation: The in-degree centrality of each node is calculated using NetworkX functions.
Out-Degree Centrality Calculation: The out-degree centrality of each node is calculated using NetworkX functions.
Undirected Graph Conversion: The directed graph is converted to an undirected graph.
Total Degree Centrality Calculation: The total degree centrality of each node in the undirected graph is calculated using NetworkX functions.
Printing Centrality Measures: The centrality measures (in-degree, out-degree, and total degree) are printed for each node.
Output
The script will print the in-degree, out-degree, and total degree centrality measures for each node in the graph
