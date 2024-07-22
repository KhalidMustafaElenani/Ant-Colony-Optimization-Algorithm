# Ant Colony Optimization Algorithm
![Swarm_intelligence](https://img.shields.io/badge/Swarm%20intelligence%20-%20brown?style=plastic)
![Ant_Colony_Optimization](https://img.shields.io/badge/Ant_Colony_Optimization-2011-%20teal?style=plastic)
![License](https://img.shields.io/badge/license%20-%20MIT%20-%20darkred?style=plastic)
![Python Version](https://img.shields.io/badge/Python-3-%20teal?style=plastic)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Open_Issues](https://img.shields.io/badge/Issues%20-%200%20-%20orange?style=plastic)

## Description
This repository contains a Python implementation of the Ant Colony Optimization (ACO) algorithm. ACO is a stochastic, population-based optimization method inspired by the behavior of real ant colonies. It simulates the actions of ants to solve discrete optimization problems, such as the Traveling Salesman Problem (TSP) and other NP-hard problems.

The ACO algorithm uses a set of software agents (ants) to explore possible solutions. It has been widely successful in various optimization tasks, including vehicle routing, network routing, and assembly line balancing.

## Installation
1. Clone the repository: `git clone https://github.com/KhalidMustafaElenani/Ant-Colony-Optimization-Algorithm.git`
2. Navigate to the project directory: `cd Ant-Colony-Optimization-Algorithm`

## Usage Examples
  - Run the PSO algorithm by executing the main.py file: `python ACO_algorithm.ipynb`

## Example Output
```
Iteration 1: 	Shortest Path: 0 -> 3 -> 1 -> 2      Distance = 16 		Pheromone Level: 112
Iteration 2: 	Shortest Path: 1 -> 2 -> 3 -> 0      Distance = 9 		Pheromone Level: 159
Iteration 3: 	Shortest Path: 0 -> 3 -> 2 -> 1      Distance = 9 		Pheromone Level: 133
Iteration 4: 	Shortest Path: 1 -> 0 -> 3 -> 2      Distance = 10 		Pheromone Level: 221
Iteration 5: 	Shortest Path: 0 -> 3 -> 2 -> 1      Distance = 9 		Pheromone Level: 255
Iteration 6: 	Shortest Path: 1 -> 0 -> 3 -> 2      Distance = 10 		Pheromone Level: 408
Iteration 7: 	Shortest Path: 0 -> 1 -> 2 -> 3      Distance = 10 		Pheromone Level: 286
Iteration 8: 	Shortest Path: 0 -> 1 -> 2 -> 3      Distance = 10 		Pheromone Level: 359
Iteration 9: 	Shortest Path: 0 -> 1 -> 2 -> 3      Distance = 10 		Pheromone Level: 441
Iteration 10: 	Shortest Path: 1 -> 2 -> 3 -> 0      Distance = 9 		Pheromone Level: 414
==============================================================================================================
Final Solution: 	[1, 2, 3, 0],    Distance = 9, 	  Pheromone Level: 414
```
  - Through the collaborative effort of multiple ants and the pheromone updating mechanism, the algorithm effectively identifies a path that minimizes distance while maximizing pheromone presence, showcasing the efficacy of the ACO paradigm in solving complex optimization problems.

## Notes
For more details on the algorithm's functionality and setup, refer to the [NOTES.md](NOTES.md).


