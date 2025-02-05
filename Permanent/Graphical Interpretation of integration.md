---
title: Graphical Interpretation of integration
date: 2025-02-05
tags:
  - Permanent
refs: 
netlinks: 
bookref:
---
# Graphical Interpretation of integration
==2025-02-05==

---
> [[Riemann Sum]] is the way to go!
---
## Theory
Integration is area under the curve bounded by a specific axis for a given interval in that particular axis.
```graph
bounds: [-10, 4, 10, -4]
elements: [
	{type: slider, def: [[6,3],[9,3],[40,43,200]]},
	{type: functiongraph, def: ["f:sin(x)"]},
	{type: riemannsum, def: ["f:sin(x)", "f:e0", left]}
]
```
Here in the graph,

Taking [[Definite Integrals|definite integral]] of $f(x)=\sin(x)$ for the interval $[a,b]$ is given by, $$\int^{a}_{b}f(x)dx$$

---
## Q&A
> [! question] How can we find the area?
> We can use [[Integration by Sum of Limits]].
> This approach draws very small rectangles with equal width from a to b then sums them.




---
# PTR

1. 