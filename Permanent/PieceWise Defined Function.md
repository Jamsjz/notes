---
title: PieceWise Defined Function
date: 2024-11-14
tags:
  - Permanent
  - Math
refs:
  - "[[Functions]]"
netlinks: 
bookref:
---
# PieceWise Defined Function
==2024-11-14

## Theory
Piece-wise defined functions -> defined differently at different condition.
1. Greatest Integer Function(floor)($\lfloor x \rfloor$)
> [!important] 
> 1. If number is int, don't touch it.
> 2. Greatest int is from left.

2. Least Integer Function(ceil)($\lceil x \rceil$)
> [!important]
> 1. If number is int, don't touch it.
> 2. Least int is from right.

3. Absolute Function($|x|$)
```desmos-graph
y=x|x>0|blue
y=-x|x<0|blue
```
4. Signum Function ($f(x)=\frac{x}{|x|}$)

```desmos-graph
\frac{x}{x}|x>0|blue
\frac{-x}{x}|x<0|blue
```

---
## Examples
1. $\lceil 1.2 \rceil=2$
2. $\lfloor 2.9 \rfloor=2$
3. $\lfloor 2 \rfloor=2$
4. $|-2|=2$
---
## Implementation
1. Floor
```python
def floor(x: float):
	return int(x)
print(floor(2.9))
```
2. Ceil
```python
def ceil(x):
	return int(x)+1 if isinstance(x, float) else x

print(ceil(2.5))
```
2. Absolute
```python
def abs(x):
	return x if x>0 else -x
print(abs(-1))
```

---
# PTR

1. different condition from break of differentiability.