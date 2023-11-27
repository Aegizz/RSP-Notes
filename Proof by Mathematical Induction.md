#Definition 
$$\text{Show that }P_n \text{ is true for n} \geq 1$$
$$\text{Show } P_1 \text{ is true,} $$
$$\text{Assume }P_k \text{ is true,}$$
$$\text{Now show } P_{k+1} \text{ is true while } P_k \text{ is true.}$$
Example using Insertion Sort:

- The basis case consist of a single element and by definition is sorted.
- In general we can assume that the first n-1 elements of array A are completed sorted after n-1 iterations of insertion sort
- To insert one last element x to A, we find where it goes, namely the unique spot between the biggest element less than or equal to x and the smallest element greater than x. This is done by moving all greater elements back by one position creating room for x in the desired location.

Inductive Proof Errors:

- Boundary Errors: Example in the insertion sort example, there was no definition for a minimum of maximum value or when there is a singular element.
- Cavallier Extension Claims: Adding on extra item to a given problem instance might cause the entire optimal solution to change. 

Mathematical Induction is usually the right way to verify the correctness of a recursive or incremental insertion algorithm.