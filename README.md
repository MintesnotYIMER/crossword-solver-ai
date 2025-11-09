# 🧩 Crossword Solver — DFS / BFS vs CSP (OR-Tools)

Compare uninformed search algorithms (**DFS**, **BFS**) with **Constraint Satisfaction** approaches (**python-constraint**, **OR-Tools CP-SAT**) for crossword-puzzle solving.  
CSP approaches handle larger grids efficiently through constraint propagation and domain pruning. :contentReference[oaicite:0]{index=0}

---

## 👥 Team & Roles
- **Ismael Carrasco Mkhazni** — BFS/DFS implementation  
- **Abdullah Tariq** — CSP modeling using python-constraint and OR-Tools  
- **Mintesnot Yimer** — Performance analysis, intersection and visualization utilities, report author

### 🙋 My Contributions (Mintesnot Yimer)
- Built intersection and grid visualization utilities  
- Benchmarked DFS/BFS vs CSP and analyzed scalability  
- Authored results & discussion sections; refactored solver logic for Colab use  

---

## 🧠 What This Project Does
- Parses grid files (black/white cells and clues)  
- Extracts word slots and intersections  
- Solves crosswords via three methods:  
  - **DFS/BFS** search  
  - **CSP** with `python-constraint` (for smaller grids)  
  - **CSP** with `OR-Tools CP-SAT` (for large grids)

---

## How to run
- Open this notebook: (https://colab.research.google.com/drive/1LhpFpYv-6dL7AYwHu901vP7djHr9NUlO?usp=sharing)
- Run all cells (Runtime → Run all).
- When prompted, enter:
   1 → Small Grid + Small Dictionary (python-constraint)
   2 → Large Grid + Large Dictionary (python-constraint)
   3 → Large Grid + Small Dictionary (OR-Tools CP-SAT)
- The notebook auto-loads grids and dictionaries from GitHub via RAW links (no manual uploads).
