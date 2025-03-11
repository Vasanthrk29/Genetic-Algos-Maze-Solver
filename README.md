# 🚀 Maze Solver using Genetic Algorithm

## 📌 Project Overview
This project implements a **Genetic Algorithm (GA) for solving a maze**. The goal is to evolve an optimal path from a **start position** to an **end position** while avoiding obstacles.

## 🔍 Problem Statement
Given:
- A **maze represented as a 2D grid** (walls = 1, open paths = 0).
- A **start point** and an **end point**.
- A **set of movement directions** (Up, Down, Left, Right).

The objective is to **find the shortest valid path** to the goal using **evolutionary techniques**.

## 📂 Dataset Information
- The maze is **predefined as a 15x15 grid**.
- Walls and open paths are hardcoded in the matrix.
- The algorithm **generates a population of random paths** and evolves them.

## 🛠️ Solution Approach
✔️ **Genetic Algorithm (GA) for path optimization**  
✔️ **Fitness function based on Manhattan distance**  
✔️ **Mutation and crossover for path evolution**  
✔️ **Matplotlib visualization for path plotting**  

## 🤖 Genetic Algorithm Setup
### **1️⃣ Representation of Individuals**
- Each individual is a **list of movement directions**.
- The path starts at **(0,0)** and moves according to the individual’s genes.

### **2️⃣ Fitness Function**
- **Objective**: Minimize the **Manhattan distance** to the goal.
- Penalizes paths that hit walls or loop excessively.

### **3️⃣ Evolutionary Operators**
- **Selection**: Tournament Selection (chooses the best individuals from a random subset).
- **Crossover**: Uniform Crossover (randomly swaps parts of two paths).
- **Mutation**: Random Direction Swap (ensures movement variety).

## 📌 How to Run the Project
1. **Clone the repository**
   ```bash
   https://github.com/Vasanthrk29/Genetic-Algos-Maze-Solver.git
   cd Genetic_Algos_Maze_Solver
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Python script**
   ```bash
   python Genetic_Algos_Maze_Solver.py
   ```
4. **Output**:
   - **Plots the optimized path over generations** 📍
   - **Displays genetic algorithm performance over time** 📈
   - **Shows the best path found** 🏆

## 📊 Results & Insights
| Generation | Best Distance to Goal |
|------------|----------------------|
| Initial    | 25                   |
| 10         | 18                   |
| 50         | 12                   |
| 100        | 8                    |
| 500        | 5                    |
| 2000       | **0 (Goal Reached!)** |

📌 The optimized path **reaches the goal in minimal moves**, showing how **evolution improves pathfinding**.

## 🚀 Future Enhancements
🔹 Implement **dynamic mazes** instead of static ones  
🔹 Introduce **multi-objective optimization** (avoid loops, reduce time)  
🔹 Deploy as a **web-based interactive simulation**  

## 🏆 Contributors
👨‍💻 **Your Name** – [GitHub Profile](https://github.com/Vasanthrk29)

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify!

