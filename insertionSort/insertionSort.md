# Insertion Sort Project

1. Sort the given list step by step according to insertion sort:

   - [22,27,16,2,18,6]

     > Step 1: 22, 27, 16, 2, 18, 6

     > Step 2: 22, 16, 27, 2, 18, 6

     > Step 3: 16, 22, 27, 2, 18, 6

     > Step 4: 16, 22, 2, 27, 18, 6

     > Step 5: 16, 2, 22, 27, 18, 6

     > Step 6: 2, 16, 22, 27, 18, 6

     > Step 7: 2, 16, 22, 18, 27, 6

     > Step 8: 2, 16, 18, 22, 27, 6

     > Step 9: 2, 16, 18, 22, 6, 27

     > Step 10: 2, 16, 18, 6, 22, 27

     > Step 11: 2, 16, 6, 18, 22, 27

     > Step 12: 2, 6, 16, 18, 22, 27

2. Big-O Notation:

   - Best: O(n), Average: O(n^2), Worst: O(n^2)

3. After sorting the list determine the scenario for searching number 18.

   - Original list: 22, 27, 16, 2, 18, 6
   - Sorted list : 2, 6, 16, 18, 22, 27

     > Let's say that we want to search the sorted list using ==Linear Search Algorithm==.
     >
     > > Linear Search Algorithm: Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.
     >
     > > Since number 18 is at somewhere middle searching number 18 in the list would be average case for Linear Search Algorithm.

     > What if want to use ==Binary Search Algorithm==?
     >
     > > Binary Search Algorithm: Binary Search is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(Log n)
     >
     > > If we divide the list to two equal portions first portion would be 2, 6, 16, and the second portion would be 18, 22, 27.
     > > We would find 18 after our second comparison thus searching number 18 in the list would be average case for Binary Search Algorithm.

4. Write the first 4 step for the given list according to Insertion Sort.

   - [7,3,5,8,2,9,4,15,6]

     > Step 1: 3, 7, 5, 8, 9, 4, 15, 6

     > Step 2: 3, 5, 7, 8, 9, 4, 15, 6

     > Step 3: 3, 5, 7, 8, 9, 4, 15, 6

     > Step 4: 3, 5, 7, 8, 9, 4, 15, 6
