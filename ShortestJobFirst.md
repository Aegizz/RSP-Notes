#Heuristic 
#JobSelection 
#Example 

$$ While (I \neq \text{ null})$$
$$\text{Accept the shortest possible job j from I}$$
$$\text{Delete j, and any interval which intersects j from I.}$$
Works unless there is two longer jobs, available in a space where only one shorter job exists.
