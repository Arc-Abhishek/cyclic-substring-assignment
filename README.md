# Cyclic Substring Maximum Sum

## Problem
Find the maximum sum of a cyclic substring such that:
- Each character is unique
- Characters have values: a=1, b=2, ..., z=26

## Approach
- Used Sliding Window technique
- Converted string into circular form by doubling it
- Used HashSet to maintain uniqueness

## Time Complexity
O(n)

## How to Run
1. Compile:
   javac Problem1.java

2. Run:
   java CyclicSubstringMaxSum
