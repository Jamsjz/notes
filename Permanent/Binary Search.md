---
title: Binary Search
date: 2024-07-31
tags:
  - Permanent
refs:
  - "[[Algorithms]]"
  - "[[D&C Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Binary Search

```ad-important
title: Big O
log(n)
```

---

```ad-important
*Needs Random Access* —you need to be able to get to the middle of the
list of elements instantly.

For which you need [[Permanent/Arrays|Arrays]]
```

---

```ad-note
title: Steps
1. Guess the mid_item is item. (mid is the middle index)
2. If not see if it's too low or too high.
3. Search only left or right depending on where item lies from mid.
4. repeat till mid_item == item.
5. return mid

```

---

```python
from typing import Union, List


def binary_search(arr: Union[List[str], List[int]], item: Union[str, int]):
    low = 0
    high = len(arr) - 1
    while low <= high:
        mid = (low + high) // 2
        if item == arr[mid]:
            return mid
        elif item < arr[mid]:
            high = mid - 1
        else:
            low = mid + 1
    return None


my_list = [1, 2, 3, 4, 4]
my_names = ["a", "b", "c", "d", "e"]
print(binary_search(my_names, "c"))
print(binary_search(my_list, 4))

```

---

# References

1. [[Algorithms]]
2. [[Divide and Conquer]]