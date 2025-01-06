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
  - https://math.libretexts.org/Bookshelves/Calculus/Calculus_3e_(Apex)/01%3A_Limits/1.02%3A_Epsilon-Delta_Definition_of_a_Limit
bookref:
---
# Limit of a Function
==2024-11-14

## Theory
For a function $y=f(x)$, the limit of the function at $x_{o}$, $L$ is the value of the function when $x$ approaches $x_{o}$.

$\lim_{ x \to x_{0} }f(x)=L$ if For each $\epsilon\text{ (small number(y-axis)) }>0$, there exist a $\delta\text{ (another small number(x-axis))}$ such that, $|x-x_{o}|<\delta \implies |f(x)-L|<\epsilon$.

This means the difference between $x$ and $x_{o}$ is very small and so is the output($f(x)$) and the limit($L$), even smaller than the very small numbers $\epsilon$ $\lim_{ x \to c }f(x)=L\iff \forall\epsilon>0,\exists \delta>0\text{ s.t. } 0 < |x-c|<\delta\implies|f(x)-L|<\epsilon$kjjjjjjjjand $\delta$ respectively.

In limit we approach $x_{o}$ from minimum possible distance. So, $\delta$ is taken min{set of all possible values of $\delta$}.

> [!important] 
> To prove limit of a function, see the values for $f(x)$, $x_{o}$ ,and $L$ 

See [Khan Academy](https://www.youtube.com/watch?v=-ejyeII0i5c).

---
## Example

1. $f(x) = \begin{cases} x^2 & \text{if } x \neq 1\\ 2 & \text{if } x = 1 \end{cases}\implies\lim_{ x \to 1 } f(x)=1$

Here,
$L=1$
$c=1$
Then,
$-\epsilon\leq f(x)-1\leq\epsilon$
or, $-\epsilon+1\leq f(x)\leq\epsilon+1$
or, $-\epsilon+1\leq x^2\leq\epsilon+1$
or, $\sqrt{ -\epsilon-1 }\leq x\leq \sqrt{ \epsilon+1 }$ 
or, $x\leq \sqrt{ \epsilon+1 }\text{ }(\because\epsilon>0)$

Also,
$-\delta+1\leq x\leq \delta+1$

---
# PTR

1. $\lim_{ x \to c }f(x)=L\iff \forall\epsilon>0,\exists \delta>0\text{ s.t. } 0 < |x-c|<\delta\implies|f(x)-L|<\epsilon$