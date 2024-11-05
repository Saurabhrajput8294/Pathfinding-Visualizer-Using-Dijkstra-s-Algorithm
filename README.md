# Pathfinding Visualizer with Dijkstra's Algorithm

This project is an interactive pathfinding visualizer built with Python and Pygame. It demonstrates Dijkstra's algorithm by finding the shortest path between two user-defined points on a grid, offering real-time visualization and interactivity.

## Features

- **Interactive Grid Interface**: A 30x30 grid allows users to place start and end points, as well as obstacles.
- **Visual Feedback**:
  - **Start Node**: Marked in blue, representing the starting point for pathfinding.
  - **End Node**: Marked in red, representing the destination.
  - **Barrier Nodes**: Marked in black, representing obstacles that the path cannot traverse.
  - **Visited Nodes**: Marked in red during the search, indicating nodes the algorithm has evaluated.
  - **Path Nodes**: Marked in green, representing the shortest path from start to end.
- **Real-time Algorithm Visualization**: Watch Dijkstra's algorithm in action as it searches and finds the shortest path.
- **User Controls**:
  - **Left Click**:
    - Set start, end, and barrier nodes.
  - **Right Click**:
    - Remove nodes (start, end, or barriers).
  - **Space Bar**: Starts the visualization of Dijkstra's algorithm.

## Installation

### Requirements
- **Python 3.x**
- **Pygame Library**: Install via pip
  ```bash
  pip install pygame
