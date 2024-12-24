---
title: Limit of a Function
date: 2024-11-14
tags:
  - Permanent
  - Math
refs:
  - "[[Functions]]"
  - "[[Limit and Continuity]]"
netlinks: 
bookref: 
---
# Limit of a Function
==2024-11-14

## Theory
For a function $y=f(x)$, the limit of the function at $x_{o}$, $L$ is the value of the function when $x$ approaches $x_{o}$.

$\lim_{ x \to x_{0} }f(x)=L$ if For each $\epsilon\text{ (small number(y-axis)) }>0$, there exist a $\delta\text{ (another small number(x-axis))}$ such that, $|x-x_{o}|<\delta \implies |f(x)-L|<\epsilon$.

This means the difference between $x$ and $x_{o}$ is very small and so is the output($f(x)$) and the limit($L$), even smaller than the very small numbers $\epsilon$ and $\delta$ respectively.

In limit we approach $x_{o}$ from minimum possible distance. So, $\delta$ is taken min{set of all possible values of $\delta$}.

> [!important] 
> To prove limit of a function, see the values for $f(x)$, $x_{o}$ ,and $L$ 

---
## Example

1. $f(x) = \begin{cases} x^2 & \text{if } x \neq 1\\ 2 & \text{if } x = 1 \end{cases}\implies\lim_{ x \to 1 } f(x)=1$

---
# PTR

1. $\lim_{ x \to x_{0} }f(x)=L$ $\iff$ ($|x-x_{o}|<\delta \implies |f(x)-L|<\epsilon$)