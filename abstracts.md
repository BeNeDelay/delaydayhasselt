---
layout: page
title: Abstracts
permalink: /abstracts/
---

## Odo Diekmann (Utrecht)

### Twin semigroups and delay equations

A delay equation is a rule for extending a function of time towards the future
on the basis of the (assumed to be) known past. By translation along the
extended function one defines a dynamical system. In the standard theory, the
fundamental solution does not 'live' in the state space. As a consequence, one
has to work in order to make the variation-of-constants formula (the main tool
for deriving local stability and bifurcation results) operational.

Twin semigroup theory {% cite twinsemigroups --file references_diekmann %}
serves to eliminate this anomaly. It builds on ideas of Feller and employs the
Pettis integral in the context of a norming dual pair of spaces, as developed by
Kunze. It exploits that the rule for extension has finite dimensional range and
it allows to cover unbounded perturbations corresponding to neutral equations.

{% bibliography --file references_diekmann --cited %}

## Hans-Otto Walther (Giessen)

### Density of short solution segments by variable delay

Simple-looking autonomous delay differential equations 

$$
x'(t)=f(x(t-r))
$$

with a real function $f$ and constant time lag $r>0$ can generate complicated
(chaotic) solution behaviour, depending on the shape of $f$. The same could be
shown for equations where $r$ is replaced with a variable, state-dependent delay
$d(x_t)\in[0,r]$, even for the case $f(\xi)=-\alpha\,\xi$ linear, with
$\alpha>0$ {% cite Lani-Wayda2016 %}. Here the argument $x_t$ of the _delay functional_ $d$ is
the segment, or history, of the solution $x$ between $t-r$ and $t$ defined as
the function $x_t:[-r,0]\to\mathbb{R}$ given by $x_t(s)=x(t+s)$.

So the delay alone may be responsible for complicated solution behaviour. In
both cases the complicated behaviour which could be established occurs in a thin
dust-like invariant subset of the infinite-dimensional Banach space or
_solution manifold_ of functions $[-r,0]\to\mathbb{R}$ on which the delay
equation defines a semiflow of differentiable solution operators {% cite Lani-Wayda2016 %}
, {% cite Walther2003 %}.

The lecture presents results which grew out of an attempt to obtain complicated
motion on a larger set with non-empty interior, as certain numerical experiments
seem to suggest. In {% cite Walther2004 %} a delay functional $d:Y\to(0,r)$ was
constructed on an infinite-dimensional subset $Y$ of the space
$C^1([-r,0],\mathbb{R})$, with $r>1$, so that the equation

\begin{align}
\tag{1}
x'(t)=-\alpha\,x(t-d(x_t))
\end{align}

has a solution whose _short segments_ $x_t|_{[-1,0]}$,
$t\ge0$, are dense in the whole space $C^1([-1,0],\mathbb{R})$. This implies a
new kind of complicated behaviour of the flowline $[0,\infty)\ni t\mapsto x_t\in
C^1_r$.

The set $Y$ in {% cite Walter2019 %} is small in the sense that it has infinite
codimension, and it is not smooth like the said solution manifolds of finite
codimension. More recent work {% cite Walter2019preprint %} concerns the
construction of a delay functional on an _open_ subset of the space
$C^1([-r,0],\mathbb{R})$ so that Eq. (1) defines a nice semiflow on the solution
manifold, and has a solution whose short segments are dense in an open subset of
the space $C^1([-1,0],\mathbb{R})$.

{% bibliography --file references --cited %}

## Therese Mur (Santiago de Chile and Giessen)

### The impact of variable delay on the stability of a periodic orbit (poster)

This poster presents results from the author's thesis, which is a case study of
the impact of variable delay on the stability of a periodic orbit. If in a
simple delay differential equation the originally constant delay is made
variable then attraction to a periodic orbit is weakened, there are bifurcations
in the Floquet spectrum, and for sufficiently large variability of the delay the
periodic orbit becomes unstable, and a period-doubling bifurcation occurs.

## Thomas Erneux (Brussels)

### Hopf bifurcation for large delays, isolas of periodic solutions, multi-rhythmicity

For oscillators subject to a delayed feedback, the Hopf bifurcation is singular
in the limit of large delays {% cite 1078-0947_2013_7_3109 PhysRevE.92.042903
--file references_erneux %}. In this limit, the Hopf slow time amplitude
equation is a delay differential equation by itself with surprising properties.
We review this particular problem in the light of recent experiments {% cite
PhysRevE.99.062219 --file references_erneux %}.

Even if there are no Hopf bifurcations from a basic steady state, isolated
branches of periodic solutions may coexist with a stable steady state. We
illustrate this specific phenomenon with the time-delayed FitzHugh-Nagumo
equations, a minimal model in neurobiology {% cite PhysRevE.93.022208 MR3495771
--file references_erneux %}.

Multi-rhythmicity is the property that an oscillator subject to a delayed
feedback may admit several coexisting branches of periodic solutions with
distinct periods. We review this phenomenon for two different problems in optics
by comparing experiments and simulations of rate equation models {% cite
Friart:14 PhysRevE.91.012910 MR3495771 --file references_erneux %}.

{% bibliography --file references_erneux --cited %}

## Jan Sieber (Exeter)

### Spectrum of linear time-periodic delay equations in the limit of large delay

The talk will discuss the asymptotics of the spectrum for periodic orbits for
two cases in the limit of large delay: first, the case of bounded period and,
second, the case of period close to the delay. The latter case is similar to
traveling pulses in partial differential equations. The talk will also discuss
practical issues that occur when trying to compute eigenvalues numerically.

## Babette de Wolff (Berlin)

### Pseudospectral approximation for Hopf bifurcation of delay equations

Pseudospectral approximation for delay equations was introduced in 2005 by Breda
et al. as a tool to approximate eigenvalues of delay equations by eigenvalues of
ordinary differential equations. The pseudospectral approximation technique has
been proposed as a method for numerical bifurcation analysis, because of the
specific structure of the approximating ODEs.

In this talk, we will discuss how the pseudospectral approximation can be used
as a numerical tool for the Hopf bifurcation and we analytically study
convergence of the Lyapunov coefficient.
