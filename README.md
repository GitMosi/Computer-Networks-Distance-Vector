# Computer Networks Distance Vector

**This repository contains a Python implementation of Distance Vector Routing and Dijkstra's Algorithm for simulating and comparing their performance on network graphs.**

##  Project Overview

The project aims to implement and test two routing algorithms—Dijkstra's Algorithm and Distance Vector Routing—on a variety of network configurations. The primary objectives are:

1. Simulation of Network Graphs: Representing routers as nodes and links as edges in a graph structure.

2. Algorithm Comparison: Measuring and visualizing execution time and efficiency for both algorithms.

3. Practical Insights: Determining the optimal algorithm for real-world use cases, particularly in latency-sensitive environments like the internet.

## Features

* Network Data Input: Accepts network configuration data in Excel format, which is processed into a Pandas DataFrame for graph creation.

* Graph Visualization: Displays the network as a graph with nodes (routers) and edges (links).

* Performance Metrics:

> Execution time for both algorithms.
> Comparison charts saved as Excel files.

* Logarithmic Visualization: Uses logarithmic scaling for clear representation of execution times.

## Performance Insights

+ Dijkstra's Algorithm: Faster with a time complexity of O(|E| + |V| log |V|), making it ideal for large-scale networks like the internet.

+ Distance Vector Routing: Slower due to its complexity of O(|E||V|) but offers a simpler approach for smaller networks.


