---
title: Recursion
date: 2024-08-01
tags:
  - Permanent
refs:
  - "[[D&C Algorithms]]"
  - "[[Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Recursion

>[!abstract] Defination
>Function calling itself is recursion.

>[!cite] Liegh Caldwell
> Loops may achieve a performance gain for your
> program. Recursion may achieve a performance
> gain for your programmer. Choose which is more
> important in your situation!

> [!note] 
Each call to a function is held in [[Permanent/Stack|Stack]] is called a call stack.

> [!example]
```python
def fact(n):
# Error case
	if n < 0:
		print("error)
# Base case
	if n == 0:
		return 1
# Recusive case
	else:
		return n * fact(n-1)
```

> [!seealso] 
> [[Permanent/Divide and Conquer|Divide and Conquer]]
> [[Permanent/Euclid's Algorithm|Euclid's Algorithm]]

---

## References

1. 