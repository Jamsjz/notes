---
title: Discontinuity
date: 2024-11-17
tags:
  - Permanent
refs:
  - "[[Limit and Continuity]]"
netlinks: 
bookref: 
---
# Types of Discontinuity
==2024-11-17

## Theory
There are many types of discontinuity.
The types are jump, removable, imremovable, infinite.

---
## Examples
1. [[Continuity]]

```desmos-graph
x=y
```

2. Removable [[Discontinuity]]

Condition:
Limit exists but not same as functional value.
$\lim_{ x \to x_{o}^+ }f(x)=\lim_{ x \to x_{0}^- }f(x)\neq f(x_{o})$

$f(x) = \begin{cases} x & \text{if } x\neq 0 \\1 & \text{if } x=0\end{cases}$, 

```desmos-graph
x=y|x>0
x=y|x<0
(0,1)
```

$f(x) = \begin{cases} x & \text{if } x > 0\\ x & \text{if } x < 0 \end{cases}$, No condition for 0

```desmos-graph
x=y|x>0
x=y|x<0
```

3. Infinite Discontinuity

Condition:
Limit of the function at $x_{o}$ is $\infty$.

```desmos-graph
y=1/x^2
```

4. Jump Discontinuity 

Condition:
Left hand limit != Right hand limit

$\lim_{ x \to x_{o}^+ }f(x)\neq\lim_{ x \to x_{0}^- }f(x)$

```desmos-graph
y=x|x<1
y=x-1|x>=1
(1,0)
```

5. Oscillating Discontinuity

$y=\sin\left( \frac{1}{x} \right)$

```desmos-graph
y=\sin(1/x)
```

---
# PTR

1. 