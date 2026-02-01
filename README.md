🧠 Artificial Intelligence Search Algorithms

Phase I & Phase II Reports

This repository contains two academic projects submitted as part of the Artificial Intelligence course.
The projects focus on search algorithms and adversarial search techniques, with practical implementations and performance analysis.

📘 Phase I: Maze Search Algorithms
📌 Problem Description

A 10×10 maze represented as a 2D grid:

0 → Free cell

1 → Wall

🎯 Goal: Find a path from start (0,0) to goal (9,9).

🧩 State Space Representation

States: Free cells (x, y)

Actions: Move up, down, left, right

Transition: Move to a valid neighboring cell

Path Cost: Uniform (cost = 1 per move)

⚙️ Algorithms Implemented

Depth-First Search (DFS)

Breadth-First Search (BFS)

Uniform Cost Search (UCS)

Iterative Deepening Search (IDS)

A* Search (Manhattan Distance Heuristic)

Greedy Best-First Search

📊 Performance Comparison

Each algorithm is evaluated based on:

Path length

Execution time

Memory usage

Completeness

Optimality

🔍 Key Result:
A* Search achieved the best balance between optimality and performance.

📄 Report File

📑 Phase 1 Report.pdf

📕 Phase II: Adversarial Search – Nim Game
🎮 Game Description

The Nim Game is a two-player, turn-based, zero-sum game.

Initial State: [3, 4, 5] piles

Players:

Max player (AI)

Min player (Opponent)

Move: Remove one or more stones from a single pile

Terminal State: All piles are empty

🧠 Algorithms Implemented

Minimax Algorithm

Alpha-Beta Pruning

Both algorithms search the game tree up to a fixed depth and aim to select optimal moves.

📐 Evaluation Function

Terminal win → +1

Terminal loss → -1

Non-terminal state → Negative sum of remaining stones

This heuristic favors states closer to winning.

⚖️ Performance Comparison
Criterion	Minimax	Alpha-Beta
Nodes Expanded	High	Much Lower
Time Efficiency	Low	High
Optimality	Optimal	Optimal
Search Depth	Same	Same

✅ Conclusion: Alpha-Beta Pruning significantly improves efficiency without affecting optimality.

📄 Report File

📑 Phase 2 Report.pdf

📂 Repository Structure
AI-Search-Algorithms/
│
├── Phase 1 Report.pdf
├── Phase 2 Report.pdf
└── README.md

✨ Author

Hossam Nabil Elsabbagh
🎓 Computer Science & Artificial Intelligence
🏫 Zewail City of Science & Technology
