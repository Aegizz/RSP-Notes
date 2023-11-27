#Heuristic 
#Example 
#RobotTour 
$$\text{Closest Pair(P): } \text{Let n be the number of points in set } P$$
$$\text{For } i = 1 \text{ to } n-1 \text{ do}$$
$$ d = \infty$$
$$\text{For each pair of endpoints (s, t) from distinct vertex chains}$$
$$\text{if dist(s,t) } \leq \text{then } s_m = s, t_m = t \text{ and } d = dist(s,t)$$
$$\text{Connect } (s_m, t_m) \text{ by an edge}$$
$$\text{Connect the two endpoints by an edge}$$
This closest pair rule can result in correct answers sometimes.
It is more complicated than Nearest Neighbour, but is correct sometimes when Nearest Neighbour is not.

