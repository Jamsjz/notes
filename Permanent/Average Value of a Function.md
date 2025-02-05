---
title: Average Value of a Function
date: 2025-02-05
tags: Permanent
refs: 
netlinks:
bookref: 
---
# Average Value of a Function
==2025-02-05==

---
> Don't go raging!
---
## Theory
The **average value** of a continuous [[Function]] $f(x)$ on a closed interval $[a, b]$ is defined as:
$$
\text{Average Value} = \frac{1}{b - a} \int_a^b f(x) \, dx
$$

 This formula calculates the mean height of the function $f(x)$ over the interval $[a, b]$, where $\int_a^b f(x) \, dx$ represents the total area under the curve, and $\frac{1}{b - a}$ normalizes this area by dividing it by the length of the interval.


It is related to [[Mean Value Theorem]] such that:
For a [[Function]] continuous over $[a,b]$, $\exists$ $c\in[a,b]$ such that,
$$
f(c)= \frac{1}{b - a} \int_a^b f(x) \, dx
$$

### Using the Fundamental Theorem of Calculus

The **Fundamental Theorem of Calculus (Part 2)** allows us to compute the definite integral $\int_a^b f(x) \, dx$ by finding an antiderivative $F(x)$ of $f(x)$:
$$
\int_a^b f(x) \, dx = F(b) - F(a)
$$
Substituting this into the formula for average value gives:
$$
\text{Average Value} = \frac{1}{b - a} \left[ F(b) - F(a) \right]
$$
where $F'(x) = f(x)$.

---
### General Interpretation
The average value formula provides a way to calculate the "mean height" of a function over an interval. By using the Fundamental Theorem of Calculus to evaluate definite integrals, we can efficiently compute this value for any continuous function.