# AlgoVisualizer

Interactive visualizer for classic interview/DSA patterns — currently covers two-pointer reverse string, with more patterns coming.

## Live Demo
[link after you deploy]

## Patterns Covered
- [x] Reverse String (Two Pointer) — O(n) time, O(1) space
- [x] Two Sum
- [x] Sliding Window
- [x] Binary Search
- [x] Bubble sort
## Patterns Implemented

### 1. Reverse String — Two Pointer
Two pointers start at opposite ends of the string and move toward each other, swapping characters at each step until they meet. Demonstrates the **two-pointer technique**, one of the most common interview patterns used to solve array/string problems without extra memory.
**Time:** O(n) **Space:** O(1)

### 2. Two Sum — Brute Force vs HashMap
Given an array and a target, find two numbers that add up to it. Includes two switchable modes:
- **Brute Force:** checks every possible pair of numbers — simple but slow.
- **HashMap:** stores numbers as you go, so for each new number you instantly check if its matching pair was already seen.
Comparing both side-by-side shows *why* hashmaps are preferred — not just that they exist.
**Time:** O(n²) brute force → O(n) hashmap **Space:** O(1) → O(n)

### 3. Sliding Window — Maximum Sum Subarray
Finds the maximum sum of any K consecutive elements in an array. Instead of recalculating the sum for every window from scratch, the window "slides" — adding the new element entering and subtracting the one leaving. This avoids redundant work.
**Time:** O(n) **Space:** O(1)

### 4. Binary Search
Searches a target value in a **sorted** array by repeatedly checking the middle element and discarding the half that can't contain the target. Each step cuts the search space in half, making it dramatically faster than scanning one by one.
**Time:** O(log n) **Space:** O(1)

### 5. Bubble Sort
Sorts an array by repeatedly comparing adjacent elements and swapping them if they're in the wrong order. After each full pass, the largest remaining unsorted value is guaranteed to be in its correct final position.
**Time:** O(n²) **Space:** O(1)
      

## Why I built this
Wanted a way to actually *see* how common interview patterns execute step-by-step, instead of just reading pseudocode.

## Author
P S SHEIK MD NAFIS ,RIT-POONAMALLEE-ECE STUDENT
3RD PROJECT
