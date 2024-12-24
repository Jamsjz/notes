---
title: Inverse of a Matrix
date: 2024-12-03
tags:
  - Permanent
refs: 
netlinks: 
bookref:
---
# Inverse of a Matrix
==2024-12-03

---
> To invert, it should be invertible.
---
## Theory
A matrix $A$ is said to be invertible if it's determinant is not 0 or it is not a square matrix.

$A_{m\times n}$ is invertible if:
1. $m=n$
2. $|A|\neq 0$

Then, the Inverse of the Matrix $A$ is defined as:
$$
A^{-1}=\frac{adj(A)}{|A|}
$$
where,
$adj(A)$ = [[Adjoint of a Matrix]] $A$ = $(A^c)^T$
where,
$A^c$ = [[Matrix of Cofactors]] = $[-1^{(i+j)}A_{ij}]$
where,
[[Cofactor at i,j position]] = $[-1^{(i+j)}A_{ij}]$
and,
$A_{ij}$ is the [[Minor of Matrix at i,j position.]]

---
## Implementation
To find the inverse of a given square matrix for large matrices, we use [[Partitioned Matrices]].

---
# PTR

1. 