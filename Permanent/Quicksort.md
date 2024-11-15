---
title: Quicksort
date: 2024-08-01
tags:
  - Permanent
refs:
  - "[[Algorithms]]"
  - "[[D&C Algorithms]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Quicksort

```ad-important
title: Time Complexity
Worst case: O(n^2)
Best case = avg case = O(nlog(n))
```

```ad-summary
title: Steps
1. Pick a pivot. readmore-> [[#Picking a Pivot]]
2. Partition the array into two sub-arrays: elements less than the pivot and elements greater than the pivot.
4. Call quicksort recursively on the two sub-arrays.
```

## Picking a Pivot
There are many ways of picking a pivot. The best two ways are:
1. Random pivoting
2. Median of three pivoting.

## Code
```python
def median0three(arr, arr_len):
    first, mid, last = arr[0], arr[arr_len // 2], arr[arr_len - 1]
    if first >= mid >= last:
        return mid
    elif last >= mid >= first:
        return mid
    elif mid >= first >= last:
        return first
    elif last >= first >= last:
        return first
    else:
        return last


def sort(arr):
    arr_len = len(arr)
    if arr_len <= 1:
        return arr

    pivot = median0three(arr, arr_len)
    low, pivots, high = [], [], []
    for item in arr:
        if item > pivot:
            high.append(item)
        elif item < pivot:
            low.append(item)
        else:
            pivots.append(item)
    return sort(low) + pivots + sort(high)
```


---

## References
