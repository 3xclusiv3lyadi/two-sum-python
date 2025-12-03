# Two Sum - Python Solution 

This project contains a clean and beginner-friendly Python implementation of the classic Two Sum problem using a dictionary (hashmap) to achieve **O(n)** time complexity.

Problem Statement
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to `target`.

Approach
- Iterate through the array once
- For each number, compute `needed = target - num`
- If `needed` already exists in the hashmap → return both indices
- Else, store current number with its index

Time Complexity  
O(n) — each lookup in the hashmap is O(1)

Space complexity 
O(n)

Example 
Input:
2 7 11 15
9

Output:
Indices: [0, 1]
Numbers: 2 + 7 = 9
