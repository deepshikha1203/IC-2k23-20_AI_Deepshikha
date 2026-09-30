# Lab 2 – Uninformed and Informed Search Strategies

## Objective

The objective of this lab is to implement and compare uninformed (blind) and informed search strategies for problem-solving and pathfinding.

---

## Experiments

### 1. Breadth-First Search (BFS) and Depth-First Search (DFS)

#### Problem Statement

Implement unguided graph or tree search algorithms to traverse and find paths between nodes in a given state space.

#### Algorithm Approach

* **BFS:** Explores the graph level by level using a Queue (FIFO), guaranteeing the shortest path in unweighted graphs.
* **DFS:** Explores as deep as possible along each branch using a Stack (LIFO) or recursion before backtracking.

#### Learning Outcome

Understands the mechanics of blind search, memory consumption trade-offs, and completeness of BFS versus DFS.

---

### 2. Hill Climbing, Best-First Search, and A* Search

#### Problem Statement

Implement heuristic-based search techniques to solve pathfinding and optimization problems efficiently.

#### Algorithm Approach


* **Hill Climbing:** A local search algorithm that continuously moves in the direction of increasing value (steepest ascent) to find a local maximum.
* **Best-First Search:** Uses a priority queue ordered by a heuristic function $h(n)$ to greedily explore the most promising node.
* **A* Search:** Combines path cost $g(n)$ and heuristic estimate $h(n)$ using the evaluation function $f(n) = g(n) + h(n)$ to find the optimal path.

#### Learning Outcome

Demonstrates how heuristic information guides the search process to reduce time complexity and find optimal or near-optimal solutions.
