---
title: Euclid's Algorithm
tags:
  - Permanent
date: 2024-08-01
refs:
  - "[[Algorithms]]"
  - "[[D&C Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Euclid's Algorithm

```ad-important
Works on [[Divide and Conquer]]
Conditions: args cannot be negative
Base Case: length == 2 times the breath
Recursive case: other
Finds: GCD of the length and breadth
```

## Code
```python
class Rectangle:
    def __init__(self, length, breadth):
        self.side1 = length
        self.side2 = breadth
        self.length = length
        self.breadth = breadth

    def largest_square(self, side1, side2):
        side1, side2 = self.side1, self.side2
        side1, side2 = (side1, side2) if side1 > side2 else (side2, side1)
        if side1 == 2 * side2:
            return side2
        else:
            return Rectangle(side1 - side2, side2).largest_square()
```



---

## References
