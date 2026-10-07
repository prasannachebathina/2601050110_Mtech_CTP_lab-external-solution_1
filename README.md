# Merge Sort Using Divide and Conquer

## 1. Aim

- To implement Merge Sort using the Divide-and-Conquer technique.
- To arrange student marks in ascending order.
- To display the original and sorted marks.
- To count the number of comparisons performed.
- To analyze time and auxiliary space complexity.

## 2. Problem Statement

- A university stores the marks of N students in an unsorted array.
- The examination cell needs to sort the marks in ascending order before generating the rank list.
- Merge Sort is used to sort the marks efficiently.

## 3. Algorithm

- Start the program.
- Read the number of students and their marks.
- Display the original marks.
- Divide the array into two halves.
- Recursively sort both halves.
- Merge the sorted halves into one sorted array.
- Count comparisons during the merging process.
- Display the sorted marks.
- Display the total number of comparisons.
- Stop the program.

## 4. Requirements

- Programming Language: C
- Compiler: GCC
- Platform: Linux, Windows, or Google Colab
- Header File: `stdio.h`

## 5. How to Execute

- Save the program as `merge.c`.

- Open a terminal in the folder containing the file.

- Compile the program using:

  `gcc merge.c -o merge`

- Run the program on Linux using:

  `./merge`

- On Windows, run:

  `merge.exe`

## 6. Sample Input

- Number of students: 5
- Marks:

## 7. Sample Output

- Original marks: 50 30 10 20 40
- Sorted ascending order: 10 20 30 40 50
- Number of comparisons: 8

## 8. Complexity Analysis

- Best-case time complexity: O(N log N)
- Average-case time complexity: O(N log N)
- Worst-case time complexity: O(N log N)
- Auxiliary space complexity: O(N)

## 9. Advantages

- Efficient for large datasets.
- Uses the Divide-and-Conquer technique.
- Provides predictable time complexity.
- It is a stable sorting algorithm.

## 10. Disadvantages

- Requires additional memory for merging.
- Uses extra space proportional to the input size.
- Recursive calls require additional stack memory.

## 11. Result

- The student marks were successfully sorted in ascending order using Merge Sort.
- The original marks and sorted marks were displayed.
- The number of comparisons was counted.
- The time and auxiliary space complexities were analyzed.

## 12. Conclusion

- Merge Sort efficiently sorts student marks using Divide and Conquer.
- It has O(N log N) time complexity in the best, average, and worst cases.
- Its auxiliary space complexity is O(N).
**Viva Questions**
  1. What is Merge Sort?
1. Merge Sort is a sorting algorithm.
2. It uses the Divide-and-Conquer technique.
3. It divides the array into two halves.
4. Each half is divided again.
5. This continues until single elements remain.
  
  2. What is Divide and Conquer?
1. Divide and Conquer is an algorithm design technique.
2. It divides a large problem into smaller problems.
3. Each smaller problem is solved separately.
4. The solutions are then combined.
5. Merge Sort uses this technique.
  3.  How does the merge operation work?
1. Merge combines two sorted subarrays.
2. It compares the first elements of both subarrays.
3. The smaller element is selected.
4. The selected element is placed in a temporary array.
5. The process continues until one subarray becomes empty.
   4. Is Merge Sort a stable sorting algorithm?
1. Yes, Merge Sort is a stable sorting algorithm.
2. Stability means maintaining the order of equal elements.
3. Equal elements are not unnecessarily swapped.
4. In our program, <= is used during merging.
5. This helps preserve their original order.
  5. Why is Merge Sort suitable for sorting student marks?
1. Student marks may be stored in an unsorted array.
2. Merge Sort can efficiently arrange them.
3. It sorts the marks in ascending order.
4. The sorted marks can be used for ranking.
5. It works efficiently even when N is large.
