---
title: Big O
date: 2024-07-31
tags:
  - Permanent
refs:
  - "[[Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Big O

Big O iss a notation to show growth of number of operation with the growth of input.

It shows the worst case, i.e maximum growth of no. of operations.

---

```ad-attention
It doesn't show speed in seconds. It doesn't measure anything. It is only a notation for a function that gives estimated no. of operations.

That means: O(n) and O(2n) are the same in terms of time complexity.
```

---
## O(n)
### Simple search
```python
def simple_search(listt: list, item):
	for i, guess in enumerate(listt):
		if guess == item:
			return i
```

---

## O(log(n))
[[Permanent/Binary Search|Binary Search]]

---

## O(n^2)
```python
def bubble_sort(arr: Union[List[str], List[int]]):
    n = len(arr)
    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
```

---

## O(n!)

Sales Person Problem:
Find shortest path using combinations.

---
# PTR
