#Algorithm 
#Example 
#JobSelection 
#ExhaustiveScheduling
$$j = 0$$
$$S_{max} = null$$
$$\text{For each of the } 2^n \text{ subsets } S_i \text{ of intervals I}$$
$$\text{If (} S_i \text{ is mutually non-overlapping) and (size(}S_i) \geq j)$$
$$\text{then j = size(}S_i)\text{ and }S_{max} = S_i$$
$$\text{Return }S_{max}$$
