---
title: Rank of a Matrix
date: 2025-02-08
tags: Permanent
refs: 
netlinks:
bookref: 
---
# Rank of a Matrix
==2025-02-08==

---
> <% tp.file.cursor(4) %>
---
## Theory
**Rank** of a matrix measures the **dimension of the column space** (or **row space**) of the matrix. It represents the number of **[[Linearly Independent]] columns** (or rows) in the matrix.

For an $m \times n$ matrix $A$, the **rank** is denoted as:

$$
\text{rank}(A)
$$

### Column Rank and Row Rank
- The **column rank** of $A$ is the **dimension of the column space** (the span of its column vectors).
- The **row rank** of $A$ is the **dimension of the row space** (the span of its row vectors).
- A fundamental theorem states that **column rank = row rank**, so we simply refer to **the rank of the matrix**.

## Properties of Rank
1. The **rank of an invertible $n \times n$ matrix** is $n$.
2. The **rank of a zero matrix** is $0$.
3. The **rank cannot exceed the smaller of $m$ or $n$** for an $m \times n$ matrix.

This concept is crucial in **solving linear systems**, **determining matrix invertibility**, and **understanding vector spaces**.

---
# PTR

4. 