# Lab 6 – Hill Climbing Algorithm

## Overview

This lab implements the Hill Climbing algorithm, a local search technique used in Artificial Intelligence for optimization problems. The algorithm iteratively moves toward a better solution by selecting neighboring states with improved values.

---

## Problem Description

The goal is to find an optimal solution by continuously improving the current state using a heuristic evaluation function. The algorithm stops when no better neighboring state is available.

---

## Algorithm Used

### Hill Climbing Algorithm

* Starts from an initial state
* Evaluates neighboring states
* Moves to the state with the highest improvement
* Stops when no better neighbor exists (local optimum)

---

## Key Concepts

### Local Search

* Focuses on improving current solution
* Does not explore entire search space

### Heuristic Evaluation

* Determines how good a state is
* Guides the algorithm toward optimal solution

### Limitations

* Can get stuck in:

  * Local maxima
  * Plateaus
  * Ridges

---

## Implementation Details

* Implemented using Python
* Evaluated neighboring states iteratively
* Selected best possible move at each step

---

## Files

* `lab6.ipynb` → Contains full implementation and results

---

## Learning Outcomes

* Understanding of local search techniques
* Ability to implement optimization algorithms
* Awareness of limitations of greedy approaches

---

## How to Run

1. Open the notebook using Jupyter Notebook or VS Code
2. Run all cells sequentially

---
