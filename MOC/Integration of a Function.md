---
title: Integration of a Function
date: 2024-12-29
tags:
  - MOC
refs:
---
# Integration of a Function

```dataview
list from [[]] and !outgoing([[]])
```
---
Integration of a function $f(x)$ is defined under definite and indefinite intervals.
1. [[Definite Integrals]]
2. [[Indefinite Integrals]]

### Graphical Meaning of integration.
Integration is area under the curve bounded by a specific axis for a given interval in that particular axis.

```desmos-graph
y=x
x=1|y<1|y>0
x=3|y<3|y>0
(1,0)|label:A:x=a|
(3,0)|label:B:x=b
(1,1)|label:C
(3,3)|label:D
```
Here in the graph,

Taking definite integral of $f(x)=x$ for the interval $[a,b]$ is given by, $$\int^{a}_{b}f(x)$$
For evaluating the area below the curve from a to b, we need to find the area of ABCDA.

> [! question] How can we find the area?
> We can use [[Integration by Sum of Limits]].
> This approach draws very small rectangles with equal width from a to b then sums them.
> 

---