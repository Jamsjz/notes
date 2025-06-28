---
title: Diagonal Matrix Representation Theorem
date: 2025-03-15
tags: Permanent
refs: 
netlinks:
bookref: 
---
# Diagonal Matrix Representation Theorem
==2025-03-15==

---
> <% tp.file.cursor(4) %>
---
## Theory
Diagonalization Theorem Statement:
The following statements are equivalent:
1. An $m \times m$ [[Matrices|matrix]] $A$ is diagonable iff $A$ has $m$ [[Linear Dependency|Linearly Dependent]] [[Eigenvectors]] of $A$.
2. Suppose $\left\{ \bar{v_{1}},\bar{v_{2}},\bar{v_{3}},\dots,\bar{v_{m}} \right\} \subset \mathbb{C}^m$ is a linearly independent [[Set]] of eigen[[Vector|vectors]] of $A$ with corresponding eigenvalues $\lambda_{1},\lambda_{2},\lambda_{3},\dots,\lambda_{m} \in \mathbb{C}$ (such that $A \bar{v_{i}} = \lambda_{i}\bar{v_{i}}$ for $1\leq i\leq m$). Then the matrix $P = (\bar{v_{1}}|\dots|\bar{v_{m}})$ is invertible and we have,$$
A = PDP^{-1}
$$ where, $D =\text{Diag}(\lambda_{1},\dots,\lambda_{m})$.

---
# PTR

1. 