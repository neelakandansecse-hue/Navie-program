# Pattern Matching Algorithms using Naive and KMP in Python

## Overview
This project demonstrates the implementation and comparison of two popular pattern matching algorithms:

1. Naive Pattern Matching Algorithm
2. Knuth-Morris-Pratt (KMP) Algorithm

The program:
- Accepts text and pattern input from the user
- Searches for the pattern in the text
- Displays matched positions
- Measures execution time in nanoseconds
- Compares time complexity
- Displays a bar graph comparison using Matplotlib

This project is useful for understanding:
- String searching techniques
- Algorithm efficiency
- Time complexity analysis
- Performance comparison using graphs

---

## Technologies Used

- Python 3
- Matplotlib Library

---

## Algorithms Used

### 1. Naive Pattern Matching
The Naive algorithm checks the pattern at every possible position in the text.

#### Time Complexity
- Worst Case: **O(n × m)**

Where:
- `n` = length of text
- `m` = length of pattern

---

### 2. KMP (Knuth-Morris-Pratt) Algorithm
KMP improves efficiency by avoiding unnecessary comparisons using the LPS (Longest Prefix Suffix) array.

#### Time Complexity
- Worst Case: **O(n + m)**

KMP is generally faster and more efficient for large datasets.

---

## Features

- User input for text and pattern
- Pattern occurrence detection
- Execution time measurement
- Time complexity display
- Performance comparison
- Bar chart visualization

---

## Project Structure

```text
project-folder/
│
├── navie.py
└── README.md
