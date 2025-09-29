Program 1 – Selection Sort

Aim:
To sort an array of elements using Selection Sort algorithm.

Software Used:
VS Code

Theory:
* Selection Sort is a simple comparison-based sorting algorithm.
* It divides the array into sorted and unsorted parts.
* Repeatedly selects the minimum elements from the unsorted part and swaps it with the first unsorted element.
* Works for small datasets.

Algorithm:
1. Start.
2. Consider the first element as minimum.
3. Traverse the unsorted part to find the actual minimum element.
4. Swap the minimum element with the first unsorted element.
5. Move the boundary of the sorted part one step forward.
6. Repeat steps 2–5 until the array is fully sorted.
7. Stop.

Conclusion:
* Successfully sorted the array using Selection Sort.
* Simple to understand and implement.
* Efficient for small arrays, but not suitable for large datasets due to O(n²) complexity.

Program 2 – Bubble Sort

Aim:
To sort an array of elements using Bubble Sort algorithm.

Software Used:
VS Code

Theory:
* Bubble Sort repeatedly compares adjacent elements and swaps them if they are in wrong order.
* Larger elements “bubble” to the end of the array in each pass.
* Works best for small arrays and almost sorted arrays.

Algorithm:
1. Start.
2. Compare each pair of adjacent elements in the array.
3. If the first element is greater than the second, swap them.
4. Repeat this process for all elements.
5. After each pass, the largest element moves to its correct position.
6. Repeat until no swaps are needed in a pass.
7. Stop.

Conclusion:
* Successfully sorted the array using Bubble Sort.
* Easy to implement and understand.
* Inefficient for large datasets due to O(n²) complexity.

Program 3 – Quick Sort

Aim:
To sort an array of elements using Quick Sort algorithm.

Software Used:
VS Code

Theory:
* Quick Sort** is a divide-and-conquer sorting algorithm.
* Steps:

  1. Select a pivot element.
  2. Partition the array so that elements smaller than pivot are on the left and larger are on the right.
  3. Recursively sort the left and right subarrays.
* More efficient than Bubble and Selection Sort, especially for large datasets.

Algorithm:
1. Start.
2. Choose a pivot element from the array.
3. Partition the array around the pivot.
4. Recursively apply Quick Sort on left and right subarrays.
5. Stop when subarrays have only one element.

Conclusion:
* Successfully sorted the array using Quick Sort.
* Efficient and faster than Bubble and Selection Sort for large datasets.
* Demonstrates the power of divide-and-conquer strategy.

