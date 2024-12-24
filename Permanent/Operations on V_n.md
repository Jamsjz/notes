---
title: Operations on V_n
date: 2024-11-18
tags:
  - Permanent
refs:
  - "[[Vector Space]]"
netlinks: 
bookref:
---
# Operations on V_n
==2024-11-18

---
> <% tp.file.cursor(4) %>

---
## Considerations for operations
We can perform various [[Mathematical Operations]] on $V_{n}$ .

1. [[n-Dimensional Space#Set for n-space]]
2. $\bar{x}$ and $\bar{y}$ are two n-tuples taken from $V_{n}$.
We have,
$\bar{x}=(x_{1},x_{2},x_{3},\dots,x_{n})$
and ~ly, $\bar{y}$.

## Theory
1. [[#Addition]]
2. [[#Scalar Multiplication]]
3. [[#Subtraction]]
4. [[#Multiplication]]

---
### Addition
$$\bar{x}+\bar{y}=(x_{1}+y_{1},x_{2}+y_{2},x_{3}+y_{3},\dots,x_{n}+y_{n})$$
Here, Addition is well defined [[Mathematical Operations#Q&A]].

#### [[Additive Identity]]
If we add $\bar{0}$ to $\bar{x}$ we get $\bar{x}$ itself.
So, $\bar{0}$ is an additive identity in $V_{n}$.

#### $\bar{0}$
n-tuple consisting of all elements $0$ can be interpreted in many ways. Some ways being:

1. [[#Additive Identity]]
2. [[n-space Origin]]
3. Number
4. n-tuple

### Scalar Multiplication

let $\alpha$ be a scalar, Then the scalar multiplication of $\bar{x}$ by $\alpha$ is:

$$
\alpha\bar{x}=(\alpha x_{1} ,\alpha x_{2},\alpha x_{3},\dots,\alpha x_{n})
$$
Here, Scalar Multiplication is well defined [[Mathematical Operations#Q&A]].

#### [[Additive Inverse]]
When $\alpha=-1$ then we get $-\bar{x}$.
When we add $-\bar{x}$ to $\bar{x}$ we get a n-tuple consisting of all zeros.
$\bar{0}=(0,0,0,\dots,0)$ here are n $0_{s}$.

### Subtraction

There is no subtraction operation.
But it is the combination of scalar multiplication of $\bar{y}$ with -1 and addition with $\bar{x}$ like so:
$$\bar{x}-\bar{y}=\bar{x}+(-1)\bar{y}$$
### Multiplication



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

1. 