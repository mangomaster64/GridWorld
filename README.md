# Project Title
Grid World - A Python implementation of BFS and DFS pathfinding algorithms

# Table of Contents
- Overview
- Features
- Requirements
- Code Explanation
- Usage
- Contact

# Overview
Implements a grid-based pathfinding system using Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms. The program uses a pre-defined configuration file
or user-defined configuration to construct and visualize a grid of cells and compute a path from a start cell to a goal cell using both algorithms.
The program serves to allow the user to compare the functions of the BFS and DFS algorithms.

# Features
- Grid configuration through a console interface or a pre-defined configuration file
- Visualization of the grid with start (S), goal (G), and barrier (X) cells
- Implementation of both BFS and DFS algorithms
- Path reconstruction and visualization

# Requirements
- Python 3.13 or later

# Code Explanation

## Data Structures
- "node" class: Represents each cell in the grid with properties for coordinates, type (start, goal, forbidden), and traversal information
- "GridWorld" class: Manages the entire grid of cells and provides methods for pathfinding and visualization

## Algorithms
- Breadth-First Search (BFS): 
	- Explores all neighbor nodes at the current depth before moving to nodes at the next depth
	- Guaranteed to find the shortest path
- Depth-First Search (DFS):
	- Explores as far as possible along each branch before backtracking
	- May find a path faster than BFS but doesn't guarantee the shortest path

# Usage
1. Configure the initial setup in "config.ini" (grid dimensions, positions of start, goal, and barrier cells)
2. Run the program "GridWorld.py" using python
3. Optionally, follow the console menu to:
	- Modify grid size
	- Change start/goal positions
	- Add/remove barrier cells
4. Confirm changes or use the configuration file to run both BFS and DFS algorithms 

# Contact

- Quinn Oswald: qhoswald@gmail.com
- Project URL: https://github.com/mangomaster64/GridWorld
