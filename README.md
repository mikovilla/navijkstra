# Shortest Path Algorithm

## Overview
This implementation calculates the **shortest path** between two nodes in a weighted graph using **Dijkstra's Algorithm**. The algorithm efficiently determines the minimum-cost path from a starting node to a destination node.

## Purpose
- **Find the shortest path** between two nodes in a directed weighted graph.
- **Optimize routing decisions** in networks, navigation systems, and scheduling tasks.
- **Ensure correctness** by using priority-based selection to always expand the nearest node first.

## How It Works
1. **Graph Representation**: The graph is stored as an adjacency list where each node maps to its neighbors and corresponding edge weights.
2. **Priority Queue for Efficiency**: The algorithm maintains a priority queue to always select the next closest node.
3. **Distance Tracking**: A dictionary keeps track of the shortest known distance to each node from the start.
4. **Path Reconstruction**: A separate dictionary stores previous nodes to allow path reconstruction after finding the shortest route.

## Achievements
- **Efficient Routing**: The use of a priority queue ensures fast retrieval of the shortest paths.
- **Handles Weighted Graphs**: Supports networks with weighted connections rather than assuming uniform distances.
- **Early Exit Condition**: If the destination is reached, computation stops early, improving performance.

## Applications
- **Network Routing**: Optimal packet delivery in communication networks.
- **GPS Navigation**: Finding the fastest route between locations.
- **Task Scheduling**: Determining dependencies and efficient execution order.
- **Game Pathfinding**: NPC movement logic in grid-based environments.

![Intro](https://raw.githubusercontent.com/mikovilla/navijkstra/refs/heads/main/intro.png)

## Conclusion
This implementation showcases an optimized approach for solving shortest path problems. By leveraging Dijkstra’s greedy selection strategy, it ensures accurate and efficient computation of minimum-cost routes in weighted graphs.

---


