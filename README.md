# 🧠 Artificial Intelligence Search Algorithms  
## Phase I & Phase II Reports

This repository contains two academic projects submitted as part of the Artificial Intelligence course.
The projects focus on classical search algorithms and adversarial search techniques.

---

## 📘 Phase I: Maze Search Algorithms

### 📌 Problem Description
A 10×10 maze represented as a 2D grid:
- 0 → Free cell  
- 1 → Wall  

Goal: Find a path from start (0,0) to goal (9,9).

---

### 🧩 State Space Representation
- States: Free cells (x, y)
- Actions: Up, Down, Left, Right
- Transition Function: Move to a valid neighbor
- Path Cost: Uniform (cost = 1)

---

### ⚙️ Algorithms Implemented
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- Iterative Deepening Search (IDS)
- A* Search (Manhattan Distance heuristic)
- Greedy Best-First Search

---

### 📊 Performance Evaluation
Algorithms are compared based on:
- Path length
- Execution time
- Memory usage
- Completeness
- Optimality

Best overall performance was achieved by A* Search.

---

### 📄 Report File
Phase 1 Report.pdf

---

## 📕 Phase II: Adversarial Search – Nim Game

### 🎮 Game Description
The Nim Game is a two-player, turn-based, zero-sum game.

- Initial piles: [3, 4, 5]
- Players:
  - Max player (AI)
  - Min player (Opponent)
- Action: Remove one or more stones from a single pile
- Terminal state: All piles are empty

---

### 🧠 Algorithms Implemented
- Minimax Algorithm
- Alpha-Beta Pruning

---

### 📐 Evaluation Function
- Win: +1
- Loss: -1
- Non-terminal: Negative sum of remaining stones

This heuristic favors states closer to winning.

---

### ⚖️ Performance Comparison

Criterion | Minimax | Alpha-Beta
--------- | ------- | ----------
Nodes Expanded | High | Significantly Lower
Time Efficiency | Low | High
Optimality | Optimal | Optimal

---

### 📄 Report File
Phase 2 Report.pdf

---

## 📂 Repository Structure

AI-Search-Algorithms/
├── Phase 1 Report.pdf
├── Phase 2 Report.pdf
└── README.md

---

## ✨ Author

Hossam Nabil Elsabbagh  
Computer Science & Artificial Intelligence  
Zewail City of Science & Technology  
ID: 202202228
