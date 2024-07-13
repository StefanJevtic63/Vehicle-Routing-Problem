# Vehicle Routing Problem With Time Windows

# Introduction

Vehicle Routing Problem (abbreviated as VRP) is a term used for the problem of establishing routes with a set of vehicles based on one or more warehouses and customers to which goods are to be delivered. <br>
This is a major problem in distribution and logistics even today, and was first described in 1959 by Danzig and Ramser. <br>
It can be seen as a generalization of the problem of the traveling salesman, where the minimization of the traveled distance is most often done, and nowadays the minimization of fuel consumption or time is also done. <br>
We will deal with a variant of the problem where the total elapsed time for each route is optimized. <br>

# Definition of the problem

We are located in an arbitrary city, in the center of which is a depot where all vehicles start and end their customer tour. <br>
The set of vehicles is treated as homogeneous - the vehicles are identical with the given capacity. <br>
Each customer is characterized by the quantity of requested products as well as the time interval of receiving the goods, i.e.
each vehicle must visit the customer before the expiration of the given interval, and in case of earlier arrival, it must wait. <br>
The price of each route is equivalent to the time needed to go around it with additional delays at the customer's place taken into account. <br>
We calculate the travel time between two customers using their Euclidean distance. <br>
This is an NP-hard problem on which we applied optimization algorithm with the aim of improving the elapsed time for each route.

# Algorithms used

We used the Genetic Algorithm on which we used the following operations: <br>
 - Selection: Random Selection, Tournament Selection, Roulette Selection, Rank Selection <br>
 - Crossover: Order Crossover, Partially Mapped Crossover, Best Route Better Adjustment Crossover <br>
 - Mutation via: Swap Mutation, Invert Mutation, Shaking mutation <br>

# Dataset used

- [R101](http://web.cba.neu.edu/~msolomon/r101.htm)

# Cloning of the repository via SSH

- Position yourself in the desired directory
- git clone git@github.com:StefanJevtic63/vehicle-routing-problem.git

# Authors

[Anja Cvetkovic](https://github.com/AnjaCvetkovic25/)
[Stefan Jevtic](https://github.com/StefanJevtic63)
