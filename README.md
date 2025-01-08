# Documentation: Optimization of Biscuit Placement on a Roll

## Visualizing Biscuit Placement

The visualization function demonstrates how biscuits are placed on the roll. Each biscuit type is represented by a distinct color, while unused cases are shown in white.

![Visualization Screenshot](screenshot_visualization.png)

- Yellow: Biscuit Type 0
- Orange: Biscuit Type 1
- Red: Biscuit Type 2
- Purple: Biscuit Type 3

The visual also indicates that there were 178 unused cases in this instance.

## Algorithmic Approaches

### 1. Greedy Algorithm
- **Execution Time**: 0.002 seconds
- **Performance**: 675 points with only 15 unused cases.
- **Description**: This algorithm places biscuits by maximizing the value-to-length ratio at each step. It is simple, fast, and effective for problems where local decisions yield near-optimal solutions.

### 2. Simulated Annealing
- **Execution Time**: 20 seconds
- **Performance**: Average score of 400 points with 42 unused cases.
- **Description**: Simulated Annealing explores the entire solution space and accepts worse solutions temporarily to escape local minima. However, for this problem, its exploratory nature does not yield significant benefits over the Greedy algorithm.

### 3. Genetic Algorithm
- **Execution Time**: 103 seconds (for 100 individuals and 500 generations)
- **Performance**: Achieves high scores of 690 points but generates more unused cases than the Greedy algorithm.
- **Description**: The Genetic Algorithm combines randomness and selection pressure to evolve solutions over generations. While powerful, its high computational cost is a limiting factor.

## Conclusion
The project demonstrates that:
- A simple Greedy algorithm is often sufficient for locally solvable problems, providing quick and effective results.
- Complex algorithms like Simulated Annealing and Genetic Algorithms are less effective for this particular problem due to the additional computational overhead without significant gains in performance.

![Algorithm Comparison Screenshot](screenshot_comparison.png)

## Lessons Learned
- Optimization techniques must be chosen based on problem characteristics.
- Balancing execution time and solution quality is critical in real-world applications.

This project underscores the importance of aligning algorithm complexity with problem requirements.
