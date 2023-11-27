#Example 
#InsertionSort
#Algorithm 
#Sorting
Works well on numbers and names, dependant on the appropriate comparison operation (<). 


### Insertion Sort
```c++
insertion_sort(item s[], int n){
	int i,j;
	for (i = 1; i < n; i++){
		j=i;
		while ((j>0)&&(s[j] < s[j-1])){
			swap(&s[j],&s[j-1]);
			j=j-1;
		}
	}
}
```
Step 1:
$$\displaylines{(4,3,2,10,12,1,5,6) \\ j = 1, i =1, s[1] = 3, s[0] = 4}$$
Step 2:
$$ \displaylines{(3,4,2,10,12,1,5,6)\\ j = 2, i = 2, s[2] = 2, s[1] = 4}$$
Step 3:
$$\displaylines{(3,2,4,10,12,1,5,6)\\ j = 1, i = 2, s[1] = 2,s[0]=3 }$$
Step 4:
$$\displaylines{(2,3,4,10,12,1,5,6)\\ j = 3, i = 3, s[3] = 10,s[2]=4 }$$
Step 5:
$$\displaylines{(2,3,4,10,12,1,5,6)\\ j = 4, i = 4, s[4] = 12,s[3]=10 }$$
Step 6:
$$\displaylines{(2,3,4,10,12,1,5,6)\\ j = 5, i = 5, s[5] = 1,s[4]=12 }$$
Step 7:
$$\displaylines{(2,3,4,10,1,12,5,6)\\ j = 4, i = 5, s[4] = 1,s[3]=10 }$$
Step 8:
$$\displaylines{(2,3,4,1,10,12,5,6)\\ j = 1, i = 2, s[3] = 1,s[2]=4 }$$
Step 9:
$$\displaylines{(2,3,1,4,10,12,5,6)\\ j = 1, i = 2, s[2] = 1,s[1]=3 }$$
Step 10:
$$\displaylines{(2,1,3,4,10,12,5,6)\\ j = 1, i = 2, s[1] = 1,s[0]=2 }$$
Step 11:
$$\displaylines{(1,2,3,4,10,12,5,6)\\ j = 6, i = 6, s[6] = 5,s[5]=12 }$$
......... %%If you did not get it by now you never will.%%
Last Step:

$$(1,2,3,4,5,6,10,12)$$
