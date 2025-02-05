---
title: Fundamental Theorem of Calculus - Part 1
date: 2025-02-05
tags: Permanent
refs: 
netlinks:
bookref: 
---
# Fundamental Theorem of Calculus - Part 1
==2025-02-05==

---
> <% tp.file.cursor(4) %>
---
## Theory
The **First Fundamental Theorem of Calculus** states that if $f$ is a continuous function on the closed interval $[a, b]$, and $F$ is defined as:

$$
F(x) = \int_a^x f(t) \, dt
$$


$\forall  x  \in [a, b]$,  $F$ is differentiable on the open interval $(a, b)$, and the derivative of $F$ is given by:

$$
F'(x) = f(x)
$$

This theorem essentially states that the process of integration can be reversed by differentiation. In other words, if you take the integral of a function and then differentiate that integral, you retrieve the original function.

### Implications

- This theorem confirms that every continuous function has an anti-derivative.
- It allows for the evaluation of derivatives of integrals without needing to compute the integral explicitly.

## Example
Take $f(x)=\sin x$,
then,
$$
\text{or, }F(x)=\int \sin (x) \text{ }dx=-\cos(x)
$$
$$
\text{or, } F'(x) = -\frac{d\cos(x)}{dx}=-(-\sin(x))=\sin(x)
$$
$$\therefore F'(x)=f(x)$$

---
# PTR

1. 