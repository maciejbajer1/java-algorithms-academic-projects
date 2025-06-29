# Java Algorithms

This repository contains a set of classic algorithm implementations in **Java**, developed as part of academic coursework.

1. MaxSubarray2D.java
   
Kadane’s algorithm extended to two dimensions — finds the rectangular subarray with the maximum sum.

2. TriangleCounter.java

Counts the number of index triples from a sorted array of segment lengths that can form a triangle. Uses binary search with a `SearchBinFirst(x)` method in `O(log n)` time.

3. NotationConverter.java

Converts arithmetic expressions: form ONP to INF and back.

4. BinarySearch2D.java

Binary search in a 2D matrix where each row and column is sorted in increasing order.

5. KnapsackSolver.java

Solves the subset-sum version of the knapsack problem by recursive version and iterative stack-based simulation.

6. EfficientQuickSort.java
   
QuickSort for `long[]`:
- expected time `O(n log n)`,
- no recursion or extra memory (`O(1)`),
- uses "median-of-three" pivot,
- switches to InsertionSort for small subarrays.

7. MedianOfMedians.java

Finds the k-th smallest element in linear time worst-case using the median-of-medians algorithm. No extra arrays are allocated.

8. BinarySearchTree.java
   
Basic BST operations.

9. MultiwayMerge.java
   
Merges `n` sorted sequences into one sorted sequence using a min-heap.  
Time complexity: `O(m * n log n)` for `n` sequences of length `m`.

---
