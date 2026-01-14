# numpy-statistics-calculator
# STA_Numpy

A simple NumPy-based statistics calculator that computes common descriptive statistics on a 3×3 matrix derived from a list of nine numerical values.

This project is designed as a lightweight utility for practicing NumPy array operations and basic statistical computations.

---

## Features
Given a list of exactly **nine numbers**, the function computes:

- Mean
- Variance
- Standard Deviation
- Maximum
- Minimum
- Sum

Each statistic is calculated:
- Column-wise
- Row-wise
- For the entire matrix

---

## Input Requirements
- A Python list containing **exactly 9 numeric values**
- The list is reshaped into a **3×3 NumPy matrix**

If the input list does not contain exactly nine elements, a `ValueError` is raised.

---

## Usage

```python
from sta_numpy import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)

