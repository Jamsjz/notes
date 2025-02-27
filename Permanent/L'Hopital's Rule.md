---
title: L'Hopital's Rule
date: 2025-02-03
tags: Permanent
refs:
netlinks:
bookref:
---
# L'Hopital's Rule

==2025-02-03==

---

> It's not a hospital !

---

## Theory

L'Hôpital's Rule is a method in calculus for evaluating limits of indeterminate forms, specifically $\frac{0}{0}$ and $\frac{\infty}{\infty}$. The rule states:

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}
$$

provided that the limits on the right-hand side exist.

## Conditions for Application

1. The [[Functions|functions]] $f(x)$ and $g(x)$ must be [[Differentiability of a Function|differentiable]] in an open interval around $a$, except possibly at $a$.
2. The derivative of the denominator, $g'(x)$, must not be zero near the limit point.

## Proof of L'Hôpital's Rule

To prove L'Hôpital's Rule, we start under the assumption that both functions approach zero at the limit point:

1. Assume:

   - $f(a) = 0$
   - $g(a) = 0$
   - $g'(a) \neq 0$

2. Rewrite the limit:

   $$
   L = \lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f(x) - f(a)}{g(x) - g(a)}
   $$

3. By applying the definition of the derivative:

   $$
   L = \lim_{x \to a} \frac{\frac{f(x) - f(a)}{x - a}}{\frac{g(x) - g(a)}{x - a}} = \frac{f'(a)}{g'(a)}
   $$

4. Thus, we conclude:
   $$
   L = \lim_{x \to a} \frac{f'(x)}{g'(x)}
   $$

This proof relies on the [[Continuity|continuity]] and [[Differentiability of a Function|differentiability of the functions]] involved, ensuring that we can apply derivatives to evaluate the limit.

---

# PTR

1.
