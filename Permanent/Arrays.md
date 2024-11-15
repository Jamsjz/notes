---
title: Arrays
date: 2024-08-01
tags:
  - Permanent
refs:
  - "[[Data Structures]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Arrays

```ad-note
title: Contiguos memory blocks with known length and starting address
1. The cell of arrays come one after another. 
2. We know the address of the first element and the length of array.
```

```ad-note
title: Randomly accessible
Since we know address of first element its easy to know adddress of any element by doing simple arithmetic.
```

![[Pasted image 20240801000103.png]]

```python
import numpy as np
arr = [1, "hello", 2.1]
np.array(arr)
```

```ad-note
title: Arrays store same type
All array elements should be of same type.

That mean in above case:
str will dominate others and other will be converted to string.
if str was not there, float would dominate and so on.
```

```ad-important
Generally all elements will be converted to a type that every element can be converted to.
```

---

# PTR
