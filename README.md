# Classic problems solved with genetic algorithms

## GA basic concepts:
* Gene / Individual = a possible solution of the problem. Usually, represented as a binary string or array.
* Population = a group of multiple individuals. Usually, only one population is used to solve the problem
* Crossover = the process of combining two individuals to generate another individual
* Mutation = the process of altering an individual (change 1->0 or 0->1 in the case of binary arrays)
* Selection = the process of selecting the individuals to form the next generation, based on their score (fitness function) 

1. Initialize starting population/s
2. While not done: Crossover, Mutation, Selection, \*
    
\* = Migration, Reinsertion, etc

