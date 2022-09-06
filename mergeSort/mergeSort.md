# Merge Sort Project

The Merge Sort algorithm is a sorting algorithm that is based on the Divide and Conquer paradigm. In this algorithm, the array is initially divided into two equal halves and then they are combined in a sorted manner.

[Merge sort algorithm](https://www.youtube.com/watch?v=TzeBrDU-JaY&list=PL2_aWCzGMAwKedT2KfDMB9YA5DgASZb3U&index=6)

1. Sort the given list step by step according to Merge Sort:

- [16,21,11,8,12,22]

> I will be sorting the list in increasing order.

> Step 1: [16,21,11], [8,12,22]

> Step 2: [16,21], [11], [8,12], [22]

> Step 3: [16], [21], [11], [8], [12], [22]

> Step 4: [16,21], [11], [8], [12], [22]

> Step 5: [11,16,21], [8], [12], [22]

> Step 6: [11,16,21], [8,12], [22]

> Step 7: [11,16,21], [8,12,22]

> Step 8: [8,11,12,16,21,22]

- Unsorted: [16,21,11,8,12,22], Sorted: [8,11,12,16,21,22]

2. Big-O Notation:

   - Best: O(nlogn), Average: O(nlogn), Worst: O(nlogn)
   - [Big-O Cheat Sheet ](https://www.bigocheatsheet.com)
