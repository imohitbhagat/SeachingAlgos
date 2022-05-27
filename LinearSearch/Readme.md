
A simple approach is to do a linear search, i.e  

-Start from the leftmost element of arr[] and one by one compare x with each element of arr[]

-If x matches with an element, return the index.

-If x doesn’t match with any of elements, return -1.

**The time complexity of the above algorithm is O(n).**

Linear search is rarely used practically because other search algorithms such as the binary search algorithm and hash tables allow significantly faster-searching comparison to Linear search.


**The Complexity of Linear Search Algorithm**

You have three different complexities faced while performing Linear Search Algorithm, they are mentioned as follows.

Best Case

Worst Case

Average Case

You will learn about each one of them in a bit more detail.

**Best Case Complexity**

The element being searched could be found in the first position.
In this case, the search ends with a single successful comparison.
Thus, in the best-case scenario, the linear search algorithm performs O(1) operations.

**Worst Case Complexity**

The element being searched may be at the last position in the array or not at all.
In the first case, the search succeeds in ‘n’ comparisons.
In the next case, the search fails after ‘n’ comparisons.
Thus, in the worst-case scenario, the linear search algorithm performs O(n) operations.

**Average Case Complexity**

When the element to be searched is in the middle of the array, the average case of the Linear Search Algorithm is O(n).
