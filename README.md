# algo-strategies-mini-project--Ashu
# Lab Assignment 1 – Algorithm Foundations

Course: Design and Analysis of Algorithms Lab (ENCA351)
Program: BCA (AI & DS), Semester V
Session: 2025–26
Faculty: Dr. Aarti Sangwan
Student: Ashu (Roll No. 2301201105)

## 📘 Overview

This repository contains the implementation, analysis, and comparison of foundational algorithms as part of Lab Assignment 1: Algorithm Foundations.
The document explores recursion, dynamic programming, divide-and-conquer sorting algorithms, and searching techniques.
Each algorithm includes:

Python implementation

Time and space complexity analysis

Performance outputs

Visual or tabular comparisons (where applicable)

## 🧮 Tasks & Implemented Algorithms
## 1. Fibonacci Algorithms
(i) Naïve Recursive Fibonacci

Uses plain recursion

Time Complexity: O(2^n)

Space Complexity: O(n)

Very slow for large values of n due to repetitive recomputation.

(ii) Dynamic Programming Fibonacci

Uses memoization or tabulation

Time Complexity: O(n)

Space Complexity: O(n)

Highly efficient for large inputs.

(iii) Fibonacci Comparison

Plots/outputs comparing recursive vs DP performance.

Highlights exponential vs linear growth differences.

## 2. Binary Search

Efficient searching on sorted arrays

Time Complexity: O(log n)

Space Complexity: O(1)

Demonstrated through sample outputs and dry-run behavior.

## 3. Bubble Sort

Repeated swapping of adjacent elements

Time Complexity: O(n²)

Space Complexity: O(1)

Suitable only for small datasets.

## 4. Selection Sort

Selects the minimum element in each pass

Time Complexity: O(n²)

Space Complexity: O(1)

Deterministic and in-place.

## 5. Insertion Sort

Inserts elements into a sorted portion of the array

Time Complexity: O(n²)

Space Complexity: O(1)

Performs well on nearly sorted lists.

## 6. Merge Sort

Divide-and-conquer algorithm

Time Complexity: O(n log n)

Space Complexity: O(n)

Stable and efficient for large datasets.

## 7. Quick Sort

Divide-and-conquer with partitioning

Time Complexity:

Best/Average: O(n log n)

Worst: O(n²)

Space Complexity: O(log n)

Very fast in practice; unstable but widely used.

## 8. Comprehensive Algorithm Comparison

A final table summarizes complexities and characteristics of all algorithms:

Algorithm	Time Complexity	Space Complexity	Remarks
Fibonacci (Recursive)	O(2ⁿ)	O(n)	Very slow for large n
Fibonacci (DP)	O(n)	O(n)	Efficient, uses memoization
Merge Sort	O(n log n)	O(n)	Stable, predictable performance
Quick Sort	O(n log n)	O(log n)	Fast but not stable
Insertion Sort	O(n²)	O(1)	Good for small inputs
Bubble Sort	O(n²)	O(1)	Simple but inefficient
Selection Sort	O(n²)	O(1)	In-place, deterministic
Binary Search	O(log n)	O(1)	Requires sorted input
📄 File Included

Lab_Assignment_1_Algo_report.pdf — Full documentation, outputs, complexity plots, and code execution results.

🧠 Purpose

This assignment builds a strong foundation for analyzing algorithm performance through:

Different design paradigms

Complexity reasoning

Practical execution measurements

Comparative evaluation of classic algorithms
