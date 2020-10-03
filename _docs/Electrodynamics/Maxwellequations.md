---
title: Maxwell's equations 
category: Devices
order: 1
---


# Maxwell's equations

Created: Sep 30, 2020
Created by: Seungjin Lee
Tags: Electrodynamics

Accumulated discoveries and observations which can be related to independent physical quantities such as the electric charge and the electric current led to the formulation of the electrodynamics in terms of a set of mathematical equations called Maxwell's equations. The explicit form of those equations is given by

$$\partial_{\mu} F^{\mu\nu} = j^{\nu}\\\partial_{[\mu}F_{\nu\lambda]}=0$$

where $$\mu,\nu,\lambda = 0, 1, \dots, 3$$$ and $$\partial_{\mu}=\frac{\partial}{\partial x^{\mu}}$$ for spacetime coordinates $$x^{\mu}$$. Also, $$F_{\mu\nu}$$ and $$j^{\mu}$$ are called the electromagnetic field and current respectively.

Due to the Poincaré lemma in a contractible neighborhood of the spacetime, the closedness of $$F_{\mu\nu}$$ in the second equation of Maxwell's equations implies the existence of a one-form $$A_{\mu}$$ such that

$$F_{\mu\nu}=\partial_{[\mu}A_{\nu]}.$$

The one-form $$A_{\mu}$$ is called the electromagnetic potential. 

One can easily show that under a given $$F_{\mu\nu}$$ the electromagnetic potential is not uniquely determined. Rather Maxwell's equations are invariant under the transformation

$$A_{\mu} \mapsto A_{\mu} + \partial_{\mu} \Omega.$$

The transformation in the above is called the gauge transformation and takes an important role in the formulation of the elementary particle physics.

The existence of the gauge transformation allows us to impose a condition on the electromagnetic potential by choosing an appropriate $$\Omega$$. Once we impose a condition on $$A_{\mu}$$, we have no longer the gauge freedom. Therefore, the process of defining $$A_{\mu}$$ with a given condition is called the gauge fixing. 

There have been several gauge fixations. Quite useful ones are the Coulomb gauge and the Lorenz gauge given by $$\partial_{i} A^{i} = 0,\ i = 1, 2, 3$$ and $$\partial_{\mu} A^{\mu}=0$$ respectively.

By replacing $$F_{\mu\nu}$$ in the first of Maxwell's equations with the electromagnetic potential under the Lorenz gauge one can find that

$$\partial^{\mu}\partial_{\mu}  A^{\nu} = j^{\nu}$$

which is a wave equation with the source $$j^{\nu}$$.