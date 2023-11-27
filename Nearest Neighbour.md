#Heuristic 
#RobotTour 
#Example 
#NearestNeighbour
$$\text{Pick and visit an initial point}, p_0$$
$$\text{Let } i = 0,$$
$$\text{While there are still un-visited points, } i = i + 1$$

$$\text{Find the closest un-visited point to } p_i$$
$$\text{Return }p_0 \text{ to } p_{n-1}$$
**Nearest neighbour is reasonably efficient, only looks at points twice.
Algorithm is incorrect (Does not always find the shortest path between points).

