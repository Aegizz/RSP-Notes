#Chapter

#### Algorithm is a procedure to achieve a specific task.
An algorithmic problem is specified by describing the complete set of instances it must work on and of its output after running one of these instances.

#Example 
##### Problem: Sorting
##### Input: A sequence of n keys, $$a_1, ..... , a_n.$$##### Output: The permutation (reordering) of the input sequence such that $$a_1  \le a_2 \le ..... \le a_{n-1} \leq a_n $$##### Instance of sorting could be numbers or an array of names. Determining you are dealing with a general problem is your first step towards solving it.
[[Sorting]]
##### There are three different properties for a good algorithm. Correct, efficient and easy to implement. These goals may not be simultaneously achievable.
##### In industrial applications, any program that achieve good enough answer without slowing the application down is often acceptable.
##### Best possible solutions or maximum efficiency only becomes a problem after serious performance or legal problems.

##### Correct algorithms usually come with a proof of correctness, which explains why an algorithm must take every instance of a problem to the desired result. 

[[Robot Tour Optimisation]]
#### There is a difference between algorithms and heuristics. Algorithms always produce a correct result, whereas heuristics may produce a good job but without providing any guarantee. 

#### Reasonable-looking algorithms can easily be incorrect. Algorithm correctness is a property that must be carefully demonstrated.

#### The heart of any algorithm is an idea. If the idea is not clear when you express the algorithm, then you are using too low-level a notation to describe it. 

#### Problem specifications have a set of allowed input instances and the required properties of the algorithm's output. e.g. Ask the wrong problem and you will get the wrong answer.

#### It is important in algorithm design is to narrow the set of allowable instances until there is a correct and efficient algorithm. For example, we can restrict a graph problem from general graphs down to trees or  a geometric problem from two dimensions down to one. 

[[Counter Examples]]
#### Counter-example is an instance of an algorithm's input that yields an incorrect output.

#### Good counter examples have two properties, verifiability and simplicity.

#### Searching for counterexamples is the best way to disprove the correctness of a heuristic.

#### Proof of demonstration of correctness is needed. Often mathematical induction is the method of choice. 

[[Proof by Mathematical Induction]]
#### Mathematical Induction is usually the right way to verify the correctness of a recursive or incremental insertion algorithm.
