# Problem 1 - Two Sum

## Problem
Find two distinct elements in an array whose sum equals the target and print their 0-based indices.

## Approach 1: Brute Force
Check every possible pair using two nested loops.

Time Complexity: O(n^2)
Space Complexity: O(1)

## Approach 2: HashMap
Store previously visited values and their indices. For every element, check whether its required complement already exists.

Time Complexity: O(n)
Space Complexity: O(n)

## Example

Input:
5
3 2 4 6 8
6

Output:
1 2