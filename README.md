Solves knapsack problem with a genetic algorithm

The knapsack problem is built via command line user input.

The fitness function sums the corresponding weights and values (separately) for each population member one by one.  It then compares the population member’s total weight to the knapsack capacity.  If the knapsack capacity has been exceeded by the population member’s total weight, then the fitness value is set to 0.  Otherwise, the population member’s corresponding total value is set as the fitness value and returned.

The stopping criterion has been defined as ‘the occurrence of 3 consecutive equal generational fitness value means.’  In other words, if the mean of a generation’s population members’ fitness function value is repeated 3 times in a row, the algorithm is stopped.  For example, if generations 14, 15, and 16 of a particular execution all return a generational fitness value mean of 34.6, the algorithm will halt and skip directly to plotting its results.
