# Exercise 3: Sorting Customer Orders

## Problem Understanding

Sorting customer orders based on total price helps businesses prioritize high-value orders and improve order management efficiency.

## Sorting Algorithms

### Bubble Sort

Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order.

### Insertion Sort

Insertion Sort places each element into its correct position in a sorted portion of the array.

### Quick Sort

Quick Sort uses a pivot element and partitions the array into smaller subarrays.

### Merge Sort

Merge Sort divides the array into smaller parts and merges them after sorting.

## Order Attributes

- Order ID
- Customer Name
- Total Price

## Algorithms Implemented

- Bubble Sort
- Quick Sort

## Time Complexity Analysis

| Algorithm | Best Case | Average Case | Worst Case |
|------------|------------|------------|------------|
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |

## Comparison

Bubble Sort is simple but inefficient for large datasets.

Quick Sort is faster and more suitable for large collections of orders because it reduces the number of comparisons significantly.

## Conclusion

Quick Sort is generally preferred in real-world applications due to its better average-case performance and scalability.