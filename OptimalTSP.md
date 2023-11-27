#Example
#RobotTour 
#Algorithm 
#OptimalTSP
$$d = \infty$$
$$\text{For each of the n! permutations } P_i \text{ of point set P}$$
$$\text{If (cost(}P_i\text{)} \leq \text{d) then d = cost(}P_i\text{) and }P_{min} = P_i$$
$$\text{Return } P_{min}$$
Essentially calculate the cost of all possible permutations of the Robot Tour Optimisation and return the smallest value.

Since all possible orderings are considered it is guaranteed to end up with the shortest possible tour. 

This algorithm is extremely slow/expensive.
