---
title: Energy-momentum tensor of electrodynamics 
category: Electrodynamics
order: 2
---

Created: Sep 30, 2020
Created by: Seungjin Lee
Tags: Electrodynamics

Maxwell's equations in [Maxwell's equations](https://twistors105.github.io/Electrodynamics/Maxwellequations/) imply the dissipation of the energy. In order to see this, let us consider the following quantity:

$$j^{a} F_{ab}=\partial_{c} F^{ca} F_{ab}.$$

One can rewrite the above equation as

$$\partial_{c} (F^{ca}F_{ab})-F^{ca}\partial_{c}F_{ab}\\=\partial_{c} (F^{ca}F_{ab})+\frac{1}{2}F^{ca}\partial_{b}F_{ca}$$

where we have used the closedness of the two-form $$F_{ab}$$ to obtain the second term of the second line from the second term of the first line. Thus, we have found the dissipation equation

$$\partial^{a} T_{ab} = j^{a}F_{ab}$$

where $$T_{ab} = F_{a}{}^{c} F_{cb} + \frac{1}{4} \eta_{ab} F^{cd} F_{cd}$$.

By using the dimensional analysis, one can easily show that $$T_{ab}$$ has the dimension of the energy-momentum tensor. Also, $$T_{ab}$$ is the unique conserved quantity which is covariant and quadratic in $$F_{ab}$$. Thus, we may identify $$T_{ab}$$ as the energy-momentum tensor of the system of the electromagnetic field.