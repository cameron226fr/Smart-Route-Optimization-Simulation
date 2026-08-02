# Smart Route Optimization Simulation

Python-based simulation project using graph algorithms and optimization techniques to evaluate routing decisions under dynamic traffic conditions.

## Overview

The Smart Route Optimization Simulation demonstrates how algorithmic approaches can be used to solve routing problems in dynamic environments. The system represents a city network as a weighted graph and uses optimization techniques to identify efficient travel routes while accounting for changing road conditions.

## Features

- Graph-based city network modeling
- Weighted road network simulation
- Dijkstra shortest path algorithm implementation
- Dynamic traffic condition simulation
- Multiple routing scenario evaluations
- Route performance analysis
- Route frequency analysis
- Network visualization and optimized path highlighting

## Technologies Used

- Python
- Graph Algorithms
- Dijkstra's Algorithm
- NetworkX
- Matplotlib
- Simulation Modeling

## How It Works

The simulation represents locations as nodes and roads as weighted edges within a graph structure.

Example route:

A → D → E → F → I

The system calculates the lowest-cost path between a starting location and destination using Dijkstra's algorithm.

Traffic conditions are simulated by dynamically modifying road travel times. After traffic changes occur, the algorithm recalculates the optimal route based on updated conditions.

## Simulation Analysis

The system evaluates multiple traffic scenarios and calculates:

- Average travel time
- Best-case travel time
- Worst-case travel time
- Most frequently selected routes

Example output:

--- Simulation Analysis ---

Average Travel Time: 17.0 minutes  
Best Travel Time: 13 minutes  
Worst Travel Time: 20 minutes  

--- Route Frequency Analysis ---

A → D → E → F → I selected 11 times  
A → B → E → F → I selected 9 times  

## Visualization

The project includes visual representations of the simulated transportation network and highlights optimized routes selected by the algorithm.

## Future Improvements

- Implement A* search algorithm for comparison
- Add reinforcement learning-based route optimization
- Expand simulation scale with larger transportation networks
- Incorporate real-time traffic data
- Develop interactive visualization tools

## Project Structure

Smart-Route-Optimization-Simulation/

├── Smart_Route_Optimization_Simulation.ipynb  
└── README.md

## Author

Cameron Frost
