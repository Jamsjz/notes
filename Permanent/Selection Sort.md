---
title: Selection Sort
date: 2024-08-01
tags:
  - Permanent
refs:
  - "[[Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Selection Sort

```ad-important
title:Big O
O(n^2)
```

Selects the lowest items and keep selecting the lowest item.

```ad-summary
title:Steps
1. get lowest value.
2. put it first in a new list or swap the value.
3. do it again excluding latest lowest value.
```

```python
from typing import Union, List


def smallest(arr: Union[List[str], List[int]]):
    smallest = arr[0]
    min_index = 0
    for i, item in enumerate(arr):
        if item < smallest:
            smallest = item
            min_index = i
    return min_index


def selection_sort(arr: Union[List[str], List[int]], reversed=False):
    "ascend by default, reversed-> true-> descend"
    arr_len = len(arr)
    for i in range(arr_len - 1):
        min_index = smallest(arr[i:]) + i
        arr[min_index], arr[i] = arr[i], arr[min_index]
    if reversed:
        arr.reverse()
        return arr
    return arr
```


---

## References
