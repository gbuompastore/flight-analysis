# Flight Network Analysis in Python

## Project Overview
This project is a network-based analysis of global flight routes, conducted as part of the **Graph Algorithms** course within the **Master in Data Analytics (2023)** at **Roma Tre University**. The analysis leverages network theory to study the structure and properties of the worldwide flight network.

## Dataset
The dataset represents a network of regularly occurring flights among airports worldwide. Nodes represent airports, and edges represent flight connections between them.

## Key Analysis Steps
- **Graph Construction**: Building a network where airports are nodes and flights are edges.
- **Network Classification**: Analyzing the network type (directed, weighted, etc.).
- **Topological Properties**: Measuring the number of nodes, edges, diameter, and average path length.
- **Degree Distribution**: Calculating the degree of nodes and visualizing the degree distribution.
- **Connected Components**: Identifying components and determining the existence of a giant component.
- **Centrality Measures**: Computing degree centrality, betweenness, and PageRank to find the most influential airports.
- **Community Detection**: Partitioning the network into communities to uncover structural patterns.
- **Assortativity**: Analyzing degree assortativity to assess correlations between node degrees.
- **Visualization**: Graphically representing the network to highlight key nodes and connections.

## Tools and Libraries
- **Python**
- **NetworkX** – Graph analysis library.
- **Matplotlib** – Visualization library.
- **Pandas** – Data manipulation library.

## Running the Code
The analysis is provided as a Jupyter Notebook, which can be executed to reproduce the results and visualizations.

## References
- **Course: Graph Algorithms (Roma Tre University, 2023)**.
- **NetworkX Documentation**: https://networkx.org/

## License
This project is licensed under the MIT License.
