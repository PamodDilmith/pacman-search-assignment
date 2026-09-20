# SE3062: Intelligent Systems — Pac-Man Search Algorithms

Take-Home Assignment 04: Search Algorithms in Pac-Man (Group Project).

## 🚀 Overview
Implementation of classic uninformed and informed AI search algorithms (DFS, BFS, UCS, A*) and designing admissible & consistent heuristics for finding all corners and eating all food dots in Pac-Man mazes.

---

## 👥 4-Member Task Distribution

| Member | Branch | Assigned Tasks | Files Modified |
| :--- | :--- | :--- | :--- |
| **Member 1** | `feature/member1-dfs-bfs` | **Q1**: Depth-First Search (`depthFirstSearch`)<br>**Q2**: Breadth-First Search (`breadthFirstSearch`) | `search.py` |
| **Member 2** | `feature/member2-ucs-astar` | **Q3**: Uniform Cost Search (`uniformCostSearch`)<br>**Q4**: A* Search (`aStarSearch`) | `search.py` |
| **Member 3** | `feature/member3-corners` | **Q5**: Finding All Corners Representation (`CornersProblem`)<br>**Q6**: Corners Problem Heuristic (`cornersHeuristic`) | `searchAgents.py` |
| **Member 4** | `feature/member4-food` | **Q7**: Eating All Dots Food Heuristic (`foodHeuristic`)<br>Integration & Full Suite QA | `searchAgents.py` |

---

## 🛠️ Setup & Running

### 1. Environment Setup
```bash
conda create -n cs188 python=3.11
conda activate cs188
pip install numpy matplotlib
```

### 2. Verification
Play a game of Pac-Man using the keyboard arrow keys:
```bash
python pacman.py
```

### 3. Running Autograder
To test individual questions:
```bash
python autograder.py -q q1
python autograder.py -q q2
python autograder.py -q q3
python autograder.py -q q4
python autograder.py -q q5
python autograder.py -q q6
python autograder.py -q q7
```

To run the full test suite:
```bash
python autograder.py
```

---

## 🌿 Git Branching Strategy
- `main`: Stable release branch.
- `develop`: Integration branch.
- `feature/*`: Dedicated branches for individual member contributions.
