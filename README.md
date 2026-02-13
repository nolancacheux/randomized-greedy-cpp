# Randomized Greedy Algorithms in C++

A comprehensive implementation of randomized greedy algorithms for solving classic optimization problems including the Knapsack Problem and Traveling Salesman Problem (TSP).

## Overview

This project demonstrates the power of randomized algorithms through practical implementations of two fundamental optimization problems:

- **Knapsack Problem (P1)**: Optimize item selection to maximize profit within capacity constraints
- **Traveling Salesman Problem (P2)**: Find the shortest route visiting all cities exactly once

## Key Features

- **Randomized Greedy Algorithms**: Smart probabilistic selection for better solution quality
- **Algorithm Replication**: Multiple runs with different random seeds to improve solution quality
- **File-based Input**: Flexible data loading from text files
- **Modular Design**: Clean separation of concerns with structured data types
- **Educational Framework**: Progressive implementation through guided exercises (Q1-Q12 + Bonus)

## Building and Running

Each question directory contains its own CMakeLists.txt for individual compilation:

```bash
cd TP/Q10
mkdir build && cd build
cmake ..
make
./Q10
```

## Algorithms Implemented

### Greedy Algorithms
- Traditional greedy approach for quick solutions
- Element-by-element construction without backtracking

### Randomized Greedy
- Probabilistic candidate selection from feasible sets
- Multiple solution attempts with different random seeds
- Improved solution quality through randomization

### Optimization Techniques
- Algorithm replication for solution quality improvement
- Seed management for reproducible randomness
- Performance comparison between deterministic and randomized approaches

## Input Format

The algorithms accept input from text files:

**Knapsack Problem:**
```
capacity
num_items
item1_weight item1_value
item2_weight item2_value
...
```

**TSP:**
```
num_cities
city_names
distance_matrix
```

## Educational Objectives

1. Understanding the power of replicated randomized algorithms
2. Solving dual optimization problems in a unified framework
3. File-based problem instance integration
4. Random seed manipulation for solution diversity
5. Flexible implementation with various data structures and algorithmic choices

## Requirements

- C++11 or higher
- CMake 3.10+
- Standard C++ libraries (iostream, fstream, vector, random)

## Documentation

For detailed implementation instructions and explanations, refer to the individual question directories. The complete project report is available as `Equipe19CIR2RapportTP.pdf`.

Nolan CACHEUX