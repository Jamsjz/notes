---
title: Rolle's Theorem
date: 2024-12-23
tags:
  - Permanent
refs:
  - "[[Differentiability of a Function]]"
  - "[[Continuity]]"
netlinks: 
bookref:
---
# Rolle's Theorem
==2024-12-23

---
> <% tp.file.cursor(4) %>

---
## Theory
If a function $f$ is defined on a closed interval $[a,b]$ such that:
1. $f$ is continuous on $[a,b]$.
2. f is differentiable on $(a,b)$
3. $f(a)=f(b)$
Then, There exists at least one point c in the open interval (a,b) such that the derivative $f'(c)=0$.

Mathematically,
$$
(f:[a,b]\to A):\\
\forall d \in[a,b],\lim_{ x \to d } f(x):=:f(d)\land
\forall e \in [a,b] \lim_{ h \to 0 } \frac{f(e+h)-f(e)}{h}:=:f'(c)\land \\
f(a)=f(b)\implies (\exists c \in [a,b]: f'(c)=0)
$$

---
# PTR

1. 