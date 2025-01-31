---
title: Span
date: 2024-12-11
tags:
  - Permanent
refs: 
netlinks: 
bookref:
---
# Span
==2024-12-11

---
> Span to make it beautiful
---
## Theory
Let $V$ be a [[Vector Space]] over a [[Mathematical Field|field]] $\mathbb{F}$, and let $S$ be a non-empty [[Subset|subset]] of $V$ such that $n_{o}(S)=a$ where a is a finite number.

The span of $S$, denoted as span$(S)$ or $[S]$, is the set of all possible finite [[Linear Combination of Vectors]] in $S$ and is defined as:
$$
span(S) = \{
\bar{x}:\bar{x}=c_{1}v_{1}+c_{2}v_{2}+\dots+c_{a}v_{a}
\text{ }|v_{i}\in S, c_{i}\in \mathbb{F}
\}
$$
where $c_{i}$ are scalars from the field $\mathbb{F}$, and $n$ is any non-negative integer.

---
## Facts
1. $[S]$ is a subspace of $V$.
2. $S\subset[S]\subset V$
---
## Example
$S=\{(1,0),(0,1)\}$
$[S]= span(\{(1,0),(0,1)\})=\{\bar{x}:\bar{x}=c_{1}(0,1)+c_{2}(1,0)\text{ }|\text{ }c_{1},c_{2}\in \mathbb{R}\}$
$V=\{\bar{x}:\bar{x}=(x_{1},x_{2})\text{ }|\text{ }x_{1},x_{2}\in \mathbb{R}\}$ 

---
# PTR

1. 