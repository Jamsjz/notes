---
title: Kernel of Linear Transformation
date: 2025-02-08
tags: Permanent
refs: 
netlinks:
bookref: 
---
# Kernel of Linear Transformation
==2025-02-08==

---
> <% tp.file.cursor(4) %>
---
## Theory
**Kernel** (also called the **null space**) of a linear transformation is the set of all input vectors that the transformation maps to the **zero vector**.

For a linear transformation $T: V \to W$ between two vector spaces, the **kernel** of $T$ is defined as:

$$
\ker(T) = \{ v \in V \mid T(v) = 0 \}
$$

In matrix terms, if $A$ is an $m \times n$ matrix representing a linear transformation $T: \mathbb{R}^n \to \mathbb{R}^m$, then the kernel is:

$$
\ker(A) = \{ x \in \mathbb{R}^n \mid Ax = 0 \}
$$

## Key Properties
1. The **kernel is a subspace** of the domain.
2. The **dimension of the kernel** is called the **nullity** of the transformation.
3. The **rank-nullity theorem** states:

   $$
   \text{rank}(A) + \text{nullity}(A) = n
   $$

   where $n$ is the number of columns of $A$.

## Example
Consider the matrix:

$$
A = \begin{bmatrix} 1 & 2 \\ 3 & 6 \end{bmatrix}
$$

To find $\ker(A)$, solve $Ax = 0$:

$$
\begin{bmatrix} 1 & 2 \\ 3 & 6 \end{bmatrix} \begin{bmatrix} x_1 \\ x_2 \end{bmatrix} = \begin{bmatrix} 0 \\ 0 \end{bmatrix}
$$

which simplifies to $x_1 + 2x_2 = 0$. So the kernel is:

$$
\ker(A) = \text{span} \left\{ \begin{bmatrix} -2 \\ 1 \end{bmatrix} \right\}
$$

This means that all solutions are scalar multiples of $(-2,1)$.




---
## Examples
<% tp.file.cursor(2) %>


---
## Implementation
<% tp.file.cursor(3) %>



---
## Q&A
<% tp.file.cursor(4) %>



---
# PTR

4. 