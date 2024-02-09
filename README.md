# Code Structure
## Part A
The structure of our code was relatively consistent throughout the assignment. For Part A, we first initialised important paramaters such as mutation and corssover rates.
Then initalised the target string and our random population before defining our functions. Then we started the iterations of the evolutionarly algorithm.
The evolutionarly algorithm looped until it generated the desired number of generations or the target string.
Our evolutionary algorithm was structured such that it first calculated the fitness of each individual in the population, then the average and max fitness of the population.
We then selected the fittest individuals in the population to generate the population that will undergo reprouction to form the new generation. 
Finally, at the end of the loop, we looped through the whole population cycling everyone into the mutation and crossover functions.
This structure was used for Part A and largely in Part B.
## Part B
Part B was mostly the same, save for the fact that we had to initially read in our data from the text file, and tackle 5 problem instances.
