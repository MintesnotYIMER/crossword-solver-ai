# 🧩 Comparative Evaluation of Search Algorithms for Crossword Puzzle Solving
**Course:** MIAGE 2IS – Artificial Intelligence Project  
**Year:** 2025  

---

## 👥 Team Members
- **Ismael Carrasco Mkhazni** – BFS/DFS implementation  
- **Abdullah Tariq** – CSP modeling and constraint solvers  
- **Mintesnot Yimer** – Analysis, algorithm optimization, and performance evaluation  

---

## 📋 Project Overview
This project compares three classical AI search techniques for solving crossword puzzles:
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Constraint Satisfaction Problem (CSP) modeling

The goal is to evaluate **efficiency, scalability, and accuracy** across different grid sizes and dictionary complexities.

---

## 🧩 Tools & Libraries
- **Language:** Python  
- **Libraries:** OR-Tools, python-constraint, time, itertools  
- **Environment:** Google Colab  

---

## ⚙️ Methodology
1. Implemented **DFS** and **BFS** to traverse possible word combinations.  
2. Modeled crossword as a **Constraint Satisfaction Problem** using:
   - Word length constraints  
   - Intersection consistency rules  
3. Tested across **small**, **medium**, and **large grids** with varying dictionary sizes.  

---

## 📈 Results Summary
| Algorithm | Performance | Comments |
|------------|--------------|----------|
| **BFS** | Fails beyond small grid (memory/time heavy) | Explores all possibilities |
| **DFS** | Works for small/medium grids | Depth-limited, slower for larger puzzles |
| **CSP** | ✅ **Best scalability & accuracy** | Enforces constraints efficiently |

---

## 🧠 My Contributions (Mintesnot Yimer)
- Conducted comparative **runtime and complexity analysis**.  
- Implemented **performance metrics** (nodes explored, time, success rate).  
- Helped design the **visual output** of solved crossword grids.  
- Wrote **discussion & conclusion** sections of the report.  

---

## 📊 Insights
- CSP eliminates most invalid states via constraint propagation.  
- DFS is more memory-efficient than BFS but still exponential.  
- For large-scale word problems, CSP offers **>90% reduction** in search time.  

---

## 💻 How to Run
- Open this notebook: (https://colab.research.google.com/drive/1LhpFpYv-6dL7AYwHu901vP7djHr9NUlO?usp=sharing)
- Run all cells (Runtime → Run all).
- When prompted, enter:
   1 → Small Grid + Small Dictionary (python-constraint)
   2 → Large Grid + Large Dictionary (python-constraint)
   3 → Large Grid + Small Dictionary (OR-Tools CP-SAT)
- The notebook auto-loads grids and dictionaries from GitHub via RAW links (no manual uploads).

---
  ## 🏁 Conclusion
CSP-based modeling outperformed DFS and BFS for crossword solving in both **accuracy and scalability**, demonstrating the value of constraint programming for combinatorial AI problems.

📘 [Full Report (PDF)](YOUR_PDF_LINK_HERE)  
💻 [Colab Notebook]((https://colab.research.google.com/drive/1LhpFpYv-6dL7AYwHu901vP7djHr9NUlO?usp=sharing))
