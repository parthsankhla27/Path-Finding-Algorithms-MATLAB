# Path Planning and Control for Robotic Navigation in MATLAB
Course: MMAE 501 - Engineering Analysis  
Completed: Fall 2024

## Project Overview
This project evaluates the performance of three fundamental path planning algorithms and compares them against different control strategies on a unicycle robot in a fixed environment. MATLAB simulations were used to implement and test these systems, focusing on autonomous navigation while avoiding obstacles.

## Core Features

### Path Planning Algorithms Evaluated
* A* (A-star)
* Dijkstra's Algorithm
* RRT (Rapidly-exploring Random Trees)

### Control Strategies Compared
(Used specifically with the A* algorithm for path following)
* Proportional (P)
* Proportional-Derivative (PD)
* Proportional-Integral-Derivative (PID)
* Lyapunov-based Control

## Performance Metrics
The following key metrics were analyzed and compared:
1. Steady-State Positional Error
2. Cumulative Tracking Error
3. Positional error over time
4. Tracking error over time

## Findings
The results of the simulation indicate that A* consistently provides optimal paths for static environments, while the Lyapunov controller ensures the most stable and accurate path following when executing that planned path.

---
This project is part of my academic portfolio for Autonomous Systems & Robotics Engineering.