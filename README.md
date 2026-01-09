# Year2_Algorithm_and_Machinelearing_CW2
# Algorithms and Machine Learning – Coursework 2 (MATH20017)

This repository contains my solutions for **Assessed Coursework 2** of the unit  
**Algorithms and Machine Learning (MATH20017)**, Autumn 2024.

The coursework focuses on **graph traversal algorithms, depth-first and breadth-first search,
topological sorting, greedy algorithms, and optimisation problems**.

---

## Files Included

- `CW2.ipynb`  
  Jupyter notebook containing all implementations, explanations, and test outputs.

- `CW2.pdf`  
  PDF export of the notebook with all answers visible.

- `CW2_24_MATH20017.pdf`  
  Coursework specification provided by the module.

---

## Coursework Content

### Question 1: Breadth-First Search (BFS)
- Implementation of `bfs_reachable_nodes`
- Returns all nodes reachable from a given start node
- Example application: shortest paths in unweighted graphs

---

### Question 2: Depth-First Search and Topological Sorting
- Implementation of `dfs_reachable_nodes`
- DFS-based topological sort for directed acyclic graphs
- Cycle detection using `topological_sort_DAG_check`

---

### Question 3: Largest Island Problem
- DFS-based solution for computing the maximum island area in a grid
- Uses 4-directional connectivity
- Tested using randomly generated grid maps

---

### Question 4: Greedy Algorithms
- Examples of greedy algorithms (Activity Selection, Huffman Coding)
- Modified Dijkstra’s algorithm for minimum Euclidean norm paths
- Correctness justified using greedy-choice arguments

---

### Question 5: Minimum Graph Cost
- Implementation of `min_graph_cost` using Prim’s algorithm
- Computes the minimum cost of a connected undirected graph
- Worst-case time complexity: **O(n² log n)**

---

## Running the Code

1. Open the notebook:
   ```bash
   jupyter notebook CW2.ipynb
