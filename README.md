# ApacheAge2
#Method 1 
Advantages:
Simple and intuitive implementation.
Directly follows the definition of the recurrence relation.

Disadvantages:
Recursive calls can lead to a large number of redundant computations, resulting in slower execution.
Recursion depth is limited by the stack size, which can cause stack overflow errors for large values of n.

#Method 2
Advantages:
Efficient computation by storing and reusing previously calculated values.
Avoids redundant calculations and improves performance compared to the recursive solution.

Disadvantages:
Requires an array of size n+1 to store intermediate results, which can consume memory for large values of n.

#Method 3
Advantages:
Avoids the need for an array to store intermediate results, saving memory.
More memory-efficient than the array-based iterative solution.

Disadvantages:
Similar to the array-based iterative solution, the performance can degrade for very large values of n due to the linear iteration.

#Conclusion:
In terms of performance, the iterative solutions (Option 2 and Option 3) are generally more efficient compared to the recursive solution (Option 1). Among the iterative solutions, the variable-based solution (Option 3) is slightly more memory-efficient than the array-based solution (Option 2) for large values of n.
