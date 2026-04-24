# 🏭 Assembly Line Balancing (ALB) Optimizer

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Industrial Engineering](https://img.shields.io/badge/Industrial_Engineering-Lean_Manufacturing-10b981?style=for-the-badge)

The **Assembly Line Balancing (ALB) Optimizer** is a Decision Support System designed to solve manufacturing bottleneck problems. It takes a series of assembly tasks, precedence constraints, and shift demands to dynamically group operations into optimal workstations using the **Longest Operating Time (LOT)** heuristic algorithm.

🔗 **[Explore Live Simulation (Live Demo)](https://onurfgg.github.io/alb-optimizer)**

## 📊 Mathematical Background & Methodology

Assembly Line Balancing is a classic NP-Hard problem in Operations Research. This tool simplifies the process for production engineers by applying heuristic optimization:

1. **Takt Time Calculation:** Determines the rhythmic pace of the assembly line based on `Available Shift Time / Production Demand`.
2. **Precedence Logic:** Ensures no task is assigned to a workstation before its required predecessor tasks are completed.
3. **LOT Heuristic Assignment:** When multiple tasks are eligible for assignment, the algorithm prioritizes the task with the longest duration. This greedy approach efficiently packs workstations and minimizes idle time.
4. **Line Efficiency Calculation:** Computes the overall efficiency of the line by evaluating the theoretical minimum stations versus the actual required stations.

## 🌟 Highlighted Features

* **Dynamic Takt Time Integration:** Changes in demand or shift duration instantly recalculate the Takt Time and trigger a reorganization of the line.
* **Smart Workstation Visualization:** Dynamically generates workstation cards detailing assigned tasks, cumulative time, and real-time utilization progress bars.
* **Bottleneck Prevention:** Automatically throws an exception if a single task duration exceeds the target Takt Time.
* **Responsive Dark UI:** Designed with a professional, glassmorphism-based dark theme optimized for analytical dashboards.

## ⚙️ Installation and Usage

This tool operates 100% client-side. No backend or server setup is required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/onurfgg/BU_KISMA_REPO_ADINI_YAZ.git](https://github.com/onurfgg/BU_KISMA_REPO_ADINI_YAZ.git)
