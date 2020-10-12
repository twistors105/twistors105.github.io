---
title: Maxwell's equations
category: Electrodynamics
order: 1
---

Created: Sep 30, 2020
Created by: Seungjin Lee
Tags: Electrodynamics

Accumulated discoveries and observations which can be related to independent physical quantities such as the electric charge and the electric current led to the formulation of the electrodynamics in terms of a set of mathematical equations called Maxwell's equations. The explicit form of those equations is given by

$$\partial_{a} F^{ab} = j^{b},\qquad\partial_{[a}F_{bc]}=0$$

where $$a,b,c = 0, 1, \dots, 3$$ and $$\partial_{a}=\frac{\partial}{\partial x^{a}}$$ for spacetime coordinates $$x^{a}$$. Also, $$F_{ab}$$ and $$j^{a}$$ are called the electromagnetic field and current respectively.

Due to the Poincaré lemma in a contractible neighborhood of the spacetime, the closedness of $$F_{ab}$$ in the second equation of Maxwell's equations implies the existence of a one-form $$A_{a}$$ such that

$$F_{ab}=\partial_{[a}A_{b]}.$$

The one-form $$A_{a}$$ is called the electromagnetic potential. 

One can easily show that under a given $$F_{ab}$$ the electromagnetic potential is not uniquely determined. Rather Maxwell's equations are invariant under the transformation

$$A_{a} \mapsto A_{a} + \partial_{a} \Omega.$$

The transformation in the above is called the gauge transformation and takes an important role in the formulation of the elementary particle physics.

The existence of the gauge transformation allows us to impose a condition on the electromagnetic potential by choosing an appropriate $$\Omega$$. Once we impose a condition on $$A_{a}$$, we have no longer the gauge freedom. Therefore, the process of defining $$A_{a}$$ with a given condition is called the gauge fixing. 

There have been several gauge fixations. Quite useful ones are the Coulomb gauge and the Lorenz gauge given by $$\partial_{i} A^{i} = 0,\ i = 1, 2, 3$$ and $$\partial_{a} A^{a}=0$$ respectively.

By replacing $$F_{ab}$$ in the first of Maxwell's equations with the electromagnetic potential under the Lorenz gauge one can find that

$$\partial^{a}\partial_{a}  A^{b} = j^{b}$$

which is a wave equation with the source $$j^{b}$$.