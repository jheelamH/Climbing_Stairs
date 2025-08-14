
# Climbing Stairs – Dynamic Programming Solution in Java

## Objective
Determine the number of distinct ways to climb to the top of a staircase of `n` steps,
given that you can take either 1 step or 2 steps at a time.

## Problem Statement
Given a staircase with `n` steps, find the total number of distinct ways to reach the top.

Example:
```
Input: n = 3
Output: 3
Explanation: {1+1+1, 1+2, 2+1}
```

## Approach
- Recurrence: ways(n) = ways(n-1) + ways(n-2)
- Base cases:
  - ways(1) = 1
  - ways(2) = 2
- Implemented using **Space-Optimized Dynamic Programming**.

## Instructions to Run
1. Save the file as `ClimbingStairs.java`.
2. Compile:
   ```bash
   javac ClimbingStairs.java
   ```
3. Run:
   ```bash
   java ClimbingStairs
   ```

## Sample Output
```
Number of ways to climb 5 stairs: 8
```
