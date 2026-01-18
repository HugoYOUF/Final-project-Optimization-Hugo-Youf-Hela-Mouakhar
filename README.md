# Grocery Store Path Optimization

This project studies how to optimize a shopper’s walking path inside a grocery store,
developed for the course *Optimization and Operations Research*.

## Model
The supermarket is modeled with parallel aisles and horizontal cross-aisles.
Movement is restricted to these corridors and distances are computed using
Manhattan distance, ensuring realistic and feasible paths.

## Methods
- Baseline: random shopping list order (naive behavior)
- 2-opt local search heuristic to improve the baseline
- Exact solution for small instances (permutation enumeration)

Optimized solutions are compared against the baseline.

## Files
- 'code': for the main Python script that will shows you the different solutions.


