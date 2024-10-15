# Sorting-Algorithms-2
More sorting algorithms in java 

## Radix Sort
### Time Complexity:
- Best, Average, and Worst: O(d*(n + k)) where d is the number of digits in the largest number and k is the range of digits.
### Key Points:
- Non-comparative sorting algorithm that processes digits or characters.
- Efficient for sorting integers or strings when the range is limited.
- Requires extra space (not in-place).
- Stable algorithm.

## Counting Sort
### Time Complexity:
- Best, Average, and Worst: O(n + k), where k is the range of input values.
### Key Points:
- Suitable for small ranges of integer data.
- Non-comparative algorithm that counts the occurrences of each element and calculates positions.
- Requires extra space.
- Stable sorting algorithm.

## TimSort
### Time Complexity:
- Best: O(n)
- Average: O(n log n)
- Worst: O(n log n)
### Key Points:
- Hybrid sorting algorithm (used in Python and Java).
- Combination of merge sort and insertion sort.
- Highly efficient for real-world data that has some order.

## Shell Sort
### Time Complexity:
- Best: O(n log n)
- Average: O(n^(3/2)) or O(n^2), depending on the gap sequence
- Worst: O(n²)
### Key Points:
- Variation of Insertion Sort that allows the exchange of far-apart elements.
- Uses a gap sequence (e.g., Knuth sequence), where elements are compared and swapped if needed at spaced intervals.
The gap is reduced gradually until it becomes 1, at which point it performs a final Insertion Sort.
More efficient than Insertion Sort for larger datasets but sensitive to the choice of gap sequence.
In-place sorting (requires no extra space) but not a stable algorithm.
