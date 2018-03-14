---
layout: page
use_math: true
title: Checking solutions to wave equation
---

We have claimed that solutions to the 1D wave equation $\dfrac{\partial^2 f}{\partial z^2} = \dfrac{1}{v^2}\dfrac{\partial^2 f}{\partial t^2}$ must take the form $f(z,t) = g(z-vt) + h(z+vt)$. Show explicitly that solutions of this form solve the wave equation.

We will often be interested in travelling wave solutions to the wave equation, show explicitly that $f(z,t) = A \cos [kz-\omega t+\delta]$ solves the wave equation. Use the complex version of this solution to illustrate how $v$, $k$, and $\omega$ are related.

Travelling wave solutions are really nice because we can write any periodic function f(z,t) as an infinite series sum of travelling wave solutions. Consider the following periodic function constructed from a series of functions,

$f(z,t) = \sum_n a_n \cos(k_nz-\omega_nt)$, or

$\tilde{f}(z,t) = \sum_n \tilde{A}_n e^{i (k_nz-\omega_nt)}$

Show that this function satisfies the wave equation. Can you do this same proof using a continuous description of the function?


$f(z,t) = \int a(\omega) \cos(k(\omega)z-\omega t) d\omega$, or

$\tilde{f}(z,t) = \int \tilde{A}(\omega) e^{i (k(\omega)z-\omega t)} d\omega$

where $a$, $b$, and $k$ are all functions of $\omega$....
