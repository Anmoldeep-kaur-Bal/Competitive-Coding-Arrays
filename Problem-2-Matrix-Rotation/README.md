# Problem 2 - Rotate Matrix by 90 Degrees Clockwise

## Approach 1: Extra Matrix
Create another matrix and place each element at its rotated position.

Time Complexity: O(n^2)
Space Complexity: O(n^2)

## Approach 2: In-Place
First transpose the matrix and then reverse every row.

Time Complexity: O(n^2)
Space Complexity: O(1)

## Example

Input:
3
1 2 3
4 5 6
7 8 9

Output:
7 4 1
8 5 2
9 6 3