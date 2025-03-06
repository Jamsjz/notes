---
title: Integration Formulas
date: 2025-03-02
tags: Permanent
refs: 
netlinks:
bookref: 
---
# [[Integration of a Function|Integration]] Formulas
This document lists basic integral formulas, classified by function type, including definite integrals and integration by parts.

### List of Integral Formulas (Indefinite Integrals)

*   $$\int 1 \, dx = x + C$$
*   $$\int a \, dx = ax + C$$
*   $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$ ; $n \neq -1$
*   $$\int \sin x \, dx = -\cos x + C$$
*   $$\int \cos x \, dx = \sin x + C$$
*   $$\int \sec^2 x \, dx = \tan x + C$$
*   $$\int \csc^2 x \, dx = -\cot x + C$$
*   $$\int \sec x \tan x \, dx = \sec x + C$$
*   $$\int \csc x \cot x \, dx = -\csc x + C$$
*   $$\int \frac{1}{x} \, dx = \ln |x| + C$$
*   $$\int e^x \, dx = e^x + C$$
*   $$\int a^x \, dx = \frac{a^x}{\ln a} + C$$ ; $a > 0, a \neq 1$

### Classification of Integral Formulas

Integral formulas are classified based on the following functions:

*   Rational functions
*   Irrational functions
*   Trigonometric functions
*   Inverse trigonometric functions
*   Hyperbolic functions
*   Exponential functions
*   Logarithmic functions
*   Gaussian functions

### Integral Formulas for Different Functions (Indefinite Integrals)

#### Rational Functions

*   $$\int 1 \, dx = x + C$$
*   $$\int a \, dx = ax + C$$
*   $$\int \frac{1}{x} \, dx = \ln |x| + C$$

#### Irrational Functions

*   $$\int \frac{1}{\sqrt{1-x^2}} \, dx = \sin^{-1}x + C$$
*   $$\int \frac{1}{1+x^2} \, dx = \tan^{-1}x + C$$
*   $$\int \frac{1}{|x|\sqrt{1-x^2}} \, dx = \sec^{-1}x + C$$

#### Trigonometric Functions

*   $$\int \sin x \, dx = -\cos x + C$$
*   $$\int \cos x \, dx = \sin x + C$$
*   $$\int \sec^2 x \, dx = \tan x + C$$
*   $$\int \csc^2 x \, dx = -\cot x + C$$
*   $$\int \sec x \tan x \, dx = \sec x + C$$
*   $$\int \csc x \cot x \, dx = -\csc x + C$$

#### Inverse Trigonometric Functions

*   $$\int \sin^{-1}x \, dx = x\sin^{-1}x + \sqrt{1 – x^2} + C$$
*   $$\int \cos^{-1}x \, dx = x\cos^{-1}x – \sqrt{1 – x^2} + C$$
*   $$\int \tan^{-1}x \, dx = x\tan^{-1}x – \frac{1}{2}\ln(1 + x^2) + C$$
*   $$\int \csc^{-1}x \, dx = x\csc^{-1}x + \ln(x + \sqrt{x^2- 1}) + C$$
*   $$\int \sec^{-1}x \, dx = x\sec^{-1}x – \ln(x + \sqrt{x^2- 1}) + C$$
*   $$\int \cot^{-1}x \, dx = x\cot^{-1}x + \frac{1}{2} \ln(1 + x^2) + C$$

#### Hyperbolic Functions

*   $$\int \sinh x \, dx = \cosh x + C$$
*   $$\int \cosh x \, dx = \sinh x + C$$
*   $$\int \tanh x \, dx = \ln(\cosh x) + C$$
*   $$\int \coth x \, dx = \ln|\sinh x| + C$$
*   $$\int \text{sech }x \, dx = \tan^{-1}|\sinh x| + C$$
*   $$\int \text{csch } x \, dx = \ln|\tanh \frac{x}{2}| + C$$

#### Exponential Functions

*   $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$$ ; $n \neq -1$
*   $$\int e^x \, dx = e^x + C$$
*   $$\int a^x \, dx = \frac{a^x}{\ln a} + C$$ ; $a > 0, a \neq 1$

#### Logarithmic Functions

*   $$\int \ln(ax) \, dx = x\ln(ax) - x + C$$
*   $$\int \ln x \, dx = x(\ln x - 1) + C$$
*   $$\int (\ln x)^2 \, dx = x(\ln x)^2 - 2x\ln x + 2x$$
*   $$\int \log_a x \, dx = x\log_a x - \frac{x}{\ln a} = \frac{x\ln x - x}{\ln a}$$
*   $$\int \ln(ax + b) \, dx = \frac{(ax + b)\ln(ax + b) - (ax + b)}{a}$$

### Integral Formulas for Square Root Functions

*   $$\int \sqrt{x} \, dx = \frac{2}{3}x^{3/2} + C$$
*   $$\int \sqrt{x^2 + a^2} \, dx = \frac{x}{2}\sqrt{x^2 + a^2} + \frac{a^2}{2}\ln|x + \sqrt{x^2 + a^2}| + C$$
*   $$\int \sqrt{x^2 - a^2} \, dx = \frac{x}{2}\sqrt{x^2 - a^2} - \frac{a^2}{2}\ln|x + \sqrt{x^2 - a^2}| + C$$
*   $$\int \sqrt{a^2 - x^2} \, dx = -\frac{x}{2}\sqrt{a^2 - x^2} + \frac{a^2}{2}\sin^{-1}\left(\frac{x}{a}\right) + C$$
*   $$\int \sqrt{a^2 + x^2} \, dx = \frac{x}{2}\sqrt{a^2 + x^2} + \frac{a^2}{2}\ln|x + \sqrt{a^2 + x^2}| + C$$

### Integral Formulas for Some Special Functions

*   $$\int \frac{1}{x^2 - a^2} \, dx = \frac{1}{2a}\ln\left|\frac{x - a}{x + a}\right| + C$$
*   $$\int \frac{1}{a^2 - x^2} \, dx = \frac{1}{2a}\ln\left|\frac{a + x}{a - x}\right| + C$$
*   $$\int \frac{1}{x^2 + a^2} \, dx = \frac{1}{a}\tan^{-1}\left(\frac{x}{a}\right) + C$$
*   $$\int \frac{1}{\sqrt{x^2 - a^2}} \, dx = \ln|x + \sqrt{x^2 - a^2}| + C$$
*   $$\int \frac{1}{\sqrt{a^2 - x^2}} \, dx = \sin^{-1}\left(\frac{x}{a}\right) + C$$
*   $$\int \frac{1}{\sqrt{x^2 + a^2}} \, dx = \ln|x + \sqrt{x^2 + a^2}| + C$$

### Definite Integral Formulas

*   $$\int_{a}^{\infty}f(x)dx=\lim_{b\rightarrow \infty}\left [ \int_{a}^{b}f(x)dx\right ]$$
*   $$\int_{a}^{b}f(x)dx=F(b)-F(a)$$

#### Definite Integrals: Rational or Irrational Expression

*   $$\int_{0}^{\infty }\frac{dx}{x^{2}+a^{2}}=\frac{\pi }{2a}$$
*   $$\int_{0}^{\infty }\frac{x^{m}dx}{x^{n}+a^{n}}=\frac{\pi a^{m-n+1}}{n\sin \left ( \frac{(m+1)\pi }{n} \right )},0< m+1< n$$
*   $$\int_{0}^{\infty }\frac{x^{p-1}dx}{1+x}=\frac{\pi }{\sin (p\pi )},0< p< 1$$
*   $$\int_{0}^{\infty }\frac{x^{m}dx}{1+2x\cos \beta +x^{2}}=\frac{\pi \sin (m\beta )}{\sin (m\pi )\sin \beta }$$
*   $$\int_{0}^{\infty }\frac{dx}{\sqrt{a^{2}-x^{2}}}=\frac{\pi }{2}$$
*   $$\int_{0}^{\infty }\sqrt{a^{2}-x^{2}}dx=\frac{\pi a^{2}}{4}$$

#### Definite integrals of Trigonometric Functions

-   $$\int_{0}^{\pi }\sin(mx)\sin (nx)dx=\begin{cases} 0 & \text{if } m\neq n\\ \frac{\pi }{2} & \text{if } m=n \end{cases}\;m,n\;\text{positive integers}$$ 
-   $$\int_{0}^{\pi }\cos (mx)\cos (nx)dx=\begin{cases} 0 & \text{if } m\neq n\\ \frac{\pi }{2} & \text{if } m=n \end{cases}\;m,n\;\text{positive integers}$$
-   $$\int_{0}^{\pi }\sin (mx)\cos (nx)dx=\begin{cases} 0 & \text{if } m+n \text{ even}\\ \frac{2m}{m^{2}-n^{2}} & \text{if } m+n \text{ odd} \end{cases}\;m,n\;\text{integers}$$


### Integration By Parts Formula

$$\int u \, dv = uv - \int v \, du$$


Where:
* u is a function of x
* dv is the derivative of another function v with respect to x
