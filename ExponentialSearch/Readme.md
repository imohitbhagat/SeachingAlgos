We have discussed, linear search, binary search for this problem.

**Exponential search involves two steps:**
1) Find range where element is present
2) Do Binary Search in above found range.

**How to find the range where element may be present?**

The idea is to start with subarray size 1, compare its last element with x, then try size 2, then 4 and so on until last element of a subarray is not greater. 
Once we find an index i (after repeated doubling of i), we know that the element must be present between i/2 and i (Why i/2? because we could not find a greater value in previous iteration)

**Time Complexity** : O(Log n) 

**Auxiliary Space** : The above implementation of Binary Search is recursive and requires O(Log n) space. With iterative Binary Search, we need only O(1) space.
