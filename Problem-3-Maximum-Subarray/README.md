# Problem 3 - Maximum Subarray Sum

## Approach 1: Brute Force
Generate every possible contiguous subarray and calculate its sum.

Time Complexity: O(n^2)
Space Complexity: O(1)

## Approach 2: Kadane's Algorithm
Maintain the best sum ending at the current position and update the overall maximum.

Time Complexity: O(n)
Space Complexity: O(1)

## Example

Input:
9
-2 1 -3 4 -1 2 1 -5 4

Output:
6