---
title: Oblique Asymptote
date: 2024-11-22
tags:
  - Permanent
refs: 
netlinks: 
bookref:
---
# Oblique Asymptote
==2024-11-22

---
## Theory
A function $f(x)=\frac{g(x)}{h(x)}$ has an oblique asymptote if $g(x)$ and $h(x)$ are polynomials such that $deg(g(x))-deg(h(x))=1$.

We can get the oblique asymptote by doing [[Polynomial Division]].

$\frac{g(x)}{h(x)}$ gives,

Remainder = $R$
Quotient = $Q$
Divisor = $h(x)$
Dividend = $g(x)$

Then,
$\frac{g(x)}{h(x)}=Q+\frac{R}{h(x)}$ since, $g(x)=Q*h(x)+R$

To find $Q$ and $R$, we should know [[Polynomial Division]].

---
## Examples

```desmos-graph
left=-20;right=20;
top=50;bottom=-50;
---
y=\frac{x^3-3}{2x-4}
```
---

# PTR

1. 