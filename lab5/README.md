# Lab 5 – A* Search Algorithm (Pathfinding)

## Overview

This lab implements the A* (A-Star) search algorithm, a widely used informed search technique in Artificial Intelligence. The algorithm efficiently finds the shortest path between two nodes by combining actual cost and heuristic estimation.

---

## Problem Description

The task involves finding the shortest path between cities (from Arad to Bucharest) using a graph-based representation. Each city is connected with distances, and a heuristic function is used to guide the search.

---

## Algorithm Used

### A* Search Algorithm

The A* algorithm uses the following evaluation function:

* **f(n) = g(n) + h(n)**

  * **g(n)** → Actual cost from start node to current node
  * **h(n)** → Estimated cost from current node to goal

The algorithm selects the node with the lowest **f(n)** value to explore next.

---

## Key Components

### Graph Representation

* Cities represented as nodes
* Distances represented as weighted edges

### Heuristic Function

* Estimated distance calculated using coordinates
* Helps guide the search efficiently

### Priority Queue

* Used to always expand the node with the lowest cost

---

## Implementation Details

* Used Python for implementation
* Utilized `heapq` for priority queue
* Implemented path tracking from source to destination

---

## Files

* `lab5.ipynb` → Contains full implementation and output

---

## Learning Outcomes

* Understanding of informed search algorithms
* Implementation of A* for shortest path problems
* Use of heuristics to improve efficiency
* Practical experience with graph-based problem solving

---

## How to Run

1. Open the notebook using Jupyter Notebook or VS Code
2. Run all cells sequentially

---
