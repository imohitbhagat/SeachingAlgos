
****Binary Search Approach:****

Binary Search is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to **O(Log n)**. 

**Binary Search Algorithm:**

**The basic steps to perform Binary Search are:**

1. Begin with the mid element of the whole array as search key.
2. If the value of the search key is equal to the item then return index of the search key.
3. Or if the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half.
4. Otherwise, narrow it to the upper half.
5. Repeatedly check from the second point until the value is found or the interval is empty.
 

