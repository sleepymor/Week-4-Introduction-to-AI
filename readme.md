# 🤖 Introduction to Artificial Intelligence  
## Task: N-Queen Problem & Traveling Salesman Problem (TSP) using Local Search  

---

## 📌 Overview  
This project is part of the **Introduction to Artificial Intelligence** course.  
It covers two classical AI problems:  

1. **N-Queen Problem** – a constraint satisfaction problem.  
2. **Traveling Salesman Problem (TSP)** – solved using **local search algorithms**.  

---

## 🧩 N-Queen Problem  
The **N-Queen Problem** requires placing **N queens** on an **N × N chessboard** such that no two queens attack each other.  

### 🔑 Key Concepts  
- Constraint Satisfaction Problem (CSP)  
- Backtracking Search  
- Heuristics (e.g., Minimum Conflicts)  

### ⚙️ Approach  
- Implement a solver that finds valid configurations of N queens.  
- Methods that can be used:  
  - Backtracking  
  - Local Search (Hill-Climbing, Simulated Annealing)  

### ✅ Example  
For `N = 8`, one valid solution places the 8 queens where no two share the same row, column, or diagonal.  

---

## 🚗 Traveling Salesman Problem (TSP) with Local Search  
The **Traveling Salesman Problem** asks for the shortest possible route that visits each city exactly once and returns to the origin city.  

### 🔑 Key Concepts  
- Combinatorial Optimization  
- Local Search Algorithms  
- Approximation of NP-hard problems  

### ⚙️ Approach  
- Represent cities as nodes and distances as edges.  
- Start with a random tour.  
- Improve the tour using local search techniques:  
  - Hill-Climbing  
  - Simulated Annealing  
  - Tabu Search  

### 🎯 Goal  
Find a route with **minimal travel cost (distance/time)**.  

---

## 🛠️ Implementation Details  
- **Language:** Python / Java / C++ (based on course requirements)  
- **Input:**  
  - N-Queen → board size `N`  
  - TSP → number of cities and distance matrix  
- **Output:**  
  - N-Queen → a valid board configuration  
  - TSP → optimized route and total cost  

---

## 📖 Learning Outcomes  
- Apply **constraint satisfaction** and **optimization** techniques.  
- Practice **backtracking** and **local search** algorithms.  
- Understand trade-offs between **exact** and **approximate** solutions.  
- Gain hands-on experience with **AI problem-solving**.  

---

## 👩‍💻 Authors  
- **Name:** Rizal, Gian, Ibnu, Wisnu, Dylan   
- **Course:** Introduction to Artificial Intelligence  
- **Institution:** ITK  
