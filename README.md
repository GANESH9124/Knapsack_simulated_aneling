# simulated_aneling
Problem Description
The Knapsack problem is a well-known optimization problem in computer science and operations research. The problem can be stated as follows:

Given a set of items, each with a weight and a value, determine the number of each item to include in a collection so that the total weight is less than or equal to a given limit and the total value is as large as possible.

Solution
The solution in this repository uses simulated annealing algorithm to find a near-optimal solution to the Knapsack problem. Simulated annealing is a probabilistic technique that is used for finding an approximate solution to an optimization problem.

The algorithm starts by selecting a random solution, and then iteratively improves the solution by accepting moves that improve the objective function or accepting moves that worsen the objective function with a probability that decreases over time. This allows the algorithm to avoid getting stuck in local optima and explore the search space more effectively.
