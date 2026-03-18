# AI Assignments 3

---

## Assignment 1: Dijkstra’s Algorithm (Uniform Cost Search)

Implementation of Dijkstra’s Algorithm to compute the shortest path between cities in India using real road distances.

- Graph represented using adjacency lists
- Data loaded from CSV file (`edge_list.csv`)
- Supports user input for source and destination cities

### Key Concepts
- Uniform Cost Search
- Graph traversal
- Priority Queue (Min Heap)

Code: dijkstra_india.py  
Dataset: edge_list.csv  

Example Output:
Path: Delhi -> Agra -> Jaipur
Total Distance: 450 km


---

## Assignment 2: UGV Navigation with Static Obstacles

A grid-based pathfinding problem where an Unmanned Ground Vehicle (UGV) navigates a 70×70 environment.

- Obstacles are generated randomly
- Three density levels: Low, Medium, High
- A* search used for optimal pathfinding

### Measures of Effectiveness (MoE)
- Path Length
- Straight-Line Distance
- Detour Factor
- Path Efficiency
- Nodes Expanded
- Execution Time

Code: Static_UGV.py  

---

## Assignment 3: UGV Navigation with Dynamic Obstacles

Extension of Assignment 2 where:
- Obstacles are dynamic and not known beforehand
- Environment changes during execution

### Approach
- Repeated A* (Online Replanning)
- UGV:
  1. Plans path
  2. Moves step-by-step
  3. Replans if path is blocked

### Features
- Dynamic obstacle updates
- Real-time replanning
- Path preview and grid visualization

Code: Dynamic_UGV.py  

---

## How to Run

### 1. Dijkstra (Cities)
```bash
python3 dijkstra_india.py

### 2. Static UGV
python3 Static_UGV.py

### 3. Dynamic UGV
python3 Dynamic_UGV.py

## Algorithms Used
Dijkstra’s Algorithm (Uniform Cost Search)
A* Search Algorithm
Repeated A* (Dynamic Replanning)
