# TabuSearch-VRP-TSP

## Overview  
A Tabu Search-based solver for **Vehicle Routing (VRP)** and **Traveling Salesman Problem (TSP)** with supply chain constraints. The algorithm optimizes **route planning, logistics, and transportation** by minimizing travel distance while handling capacity and warehouse restrictions.

## Features  
- **Dynamic Tabu List** to avoid revisiting previous solutions  
- **Aspiration Criteria** to allow better solutions even if tabu  
- **Multi-Restart & Mutation** for escaping local minima  
- **Penalty-Based Constraints** for capacity and warehouse locations  

## How It Works  
The algorithm iterates through possible routes, applying **tabu search** and **mutation strategies** to find the most efficient path while considering constraints. A final **convergence plot** visualizes the optimization progress.
