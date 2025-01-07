---
title: "quantum dynamical semigroups"
date: 2024-07-30
author: Seungjin Lee
id: 20240730093355
tags: [quantum-dynamics]
categories: 
    - dynamical quantum error correction
bibFile: assets/bib.json
draft: false
---

# quantum dynamical semigroups

A _quantum dynamical semigroup_ of a [Hilbert space effect algebra]({{< ref "effect-algebra.md" >}} "effect algebra") $(\mathcal{E}(H),0,I,+)$ is a set $\{\mathcal{B}(H) \xrightarrow{\Lambda_{t}} \mathcal{B}(H):t \le 0\}$ satisfying the following axioms {{<cite "alicki2007;breuerTheoryOpenQuantum2002" "7;117" >}}:
1. $\mathcal{B}(H)$ is the space of bounded linear operators of $H$,
2. $(\forall t \ge 0)$ $\Lambda_{t}$ is a linear function,
3. $(\forall t \ge 0)$ $\Lambda_{t}$ is completely positive,
4. $(\forall t \ge 0)$ $\Lambda_{t} I = I$,
5. $(\forall t,s \ge 0)$ $\Lambda_{t} \Lambda_{s} = \Lambda_{t + s}$,
6. $(\forall \omega: \mathcal{S}(\mathcal{E}(H)))$ $(\forall A: \mathcal{B}(H))$ $[0,\infty] \mapsto \mathbb{R}: t \mapsto \omega( \Lambda_{t} A)$ is continuous for $t$.

# propositions
## quantum Markovian master equations
> Let $A \in \mathcal{B}(H)$. If $A_{t} = \Lambda_{t} \triangleright A$, then there exists a densely defined linear map $\mathcal{B}(H) \xrightarrow{L} \mathcal{B}(H)$ with $\frac{d}{dt} A_{t} = L \triangleright A_{t}$. 

# references
{{< bibliography cited>}}
