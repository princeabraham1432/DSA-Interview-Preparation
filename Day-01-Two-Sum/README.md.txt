# Day 1 - Two Sum

## Problem
Given an array of integers nums and an integer target, return the indices of the two numbers such that they add up to target.

## Example
Input:
nums = [2,7,11,15]
target = 9

Output:
[0,1]

## Approach
1. Create a HashMap to store number and index.
2. For each number, calculate:
   complement = target - current number
3. Check if the complement already exists in the HashMap.
4. If yes, return the indices.
5. Otherwise, store the current number and index.

## Time Complexity
O(n)

## Space Complexity
O(n)

## Concepts Learned
- Arrays
- HashMap
- Time Complexity Optimization