---
title: "effect algebra"
date: 2024-05-23
author: twistors105
id: 20240523140658
tags: [quantum-foundation, quantum-measurement]
categories: 
    - reconstruction
bibFile: assets/bib.json
draft: false
---



# axioms
An _effect algebra_ is a set $E$ satisfying the following axioms {{<cite "plavalaGeneralProbabilisticTheories2023;gudder2002;vandewetering2019" >}}:
<!--more-->
1. there exists a symmetric binary relation $\perp$ on $E$,
2. there exists a binary operation $a \perp b \xmapsto{\oplus} a \oplus b$,
3. if $a \perp b$ then $a \oplus b = b \oplus a$,
4. if $a \perp b$ and $(a \oplus b) \perp c$ then $b \perp c$ and $a \perp (b \oplus c)$,
4. if $a \perp b$ and $(a \oplus b) \perp c$ then $a \oplus (b \oplus c) = (a \oplus b) \oplus c$,
5. there exists $1 \in E$ such that $\forall a \in E$ there exists a unique $a' \in E$ with $a \perp a'$ and $a \oplus a' = 1$, and
6. if $a \perp 1$ then $a = 0$.

---

# definitions
## summable set
A _summable set_ of $E$ is $D \subset E$ such that $\forall D'::D$ if $D'$ is finite then $\forall a_{1},a_{2},\ldots, a_{n}:D'$ if $a_{1} \oplus \ldots \oplus a_{n-1}$.
## sharp effects
A _sharp effect_ is $a \in E$ such that if $a \oplus a' = 1$, $b \le a$ and $b \le a'$ then $b = 0$ {{<cite "vandewetering2019" >}}.

---

# propositions
> $1 \oplus 0 = 1$. 

> Let $\le$ be a relation on an effect algebra $E$ such that $\forall a,b\in E$ $a \le b$ if $\exists c \in E$ with $a \perp c$ and $a \oplus c = b$. Then $\le$ is a partial ordering and $E$ is bounded by $\le$ {{<cite "gudder1998" >}}.

> Relation to logic {{<cite "foulis1994" >}}. 

> If an effect algebra admits an orderting set of [[20240524170019]] states, then it is an interval effect algebra {{<cite "dvurecenskij2013" 31 >}}.

> An effect algebra is a [[20240704081737]] partial commutative monoid. 

---

# variants
## convex effect algebra
A _convex effect algebra_ is an effect algebra $E$ satisfying the following axioms {{<cite "plavalaGeneralProbabilisticTheories2023" >}}:
1. there exists a binary operation $[0,1] \times E \rightarrow E: (\lambda, a) \mapsto \lambda a$,
2. $\forall \lambda,\mu \in [0,1]$ and $a \in E$, $\lambda (\mu a) = \mu (\lambda a)$,
3. if $\lambda + \mu  = 1$ then $\lambda a \perp \mu a$ and $\lambda a \oplus \mu a = (\lambda + \mu) a$,
4. if $a \perp b$ then $\lambda a \perp \lambda b$ and $\lambda a  \oplus \lambda b = \lambda (a + b)$,
5. $1a = a$.

---

# structures

## Hilbert space effect algebra
Let $H$ be a Hilbert space. Suppose that $p \in \mathcal{E}(H)$ iff $p$ is self-adjoint and $0 \le (x,p\triangleright x) \le (x,x)$ for all $x \in H$. Then $(\mathcal{E}(H),0,I,+)$ is an effect algebra {{<cite "gudder2002" >}}.


## interval effect algebra
Let $G$ be a partially ordered Abelian group and $u \ge 0$. For $G[0,u] = \{g \in G: 0 \le g \le u\}$ let $p \perp q$ if $p + q \le u$, and for $p \perp q$ $p \oplus q = p + q$. Then $G[0,u]$ is an effect algebra by $\perp, \oplus, 0$ and $u$ {{<cite "dvurecenskij2013" 22 >}}.


## unit interval of reals
$\forall a,b : [0,1]$ let $a \perp b$ if $a + b \le 1$. Then $[0,1]$ is an interval effect algebra by $\perp, +$ and $1$ {{<cite "dvurecenskij2013" 22 >}}.

---

# constructions

## product effect algebra
Let $E$ and $F$ be effect algebra and $E \times F$ be the product of $E$ and $F$. $\forall (a,b), (c,d): E \times F$ if $a \perp c$ and $(b \perp d)$ implies $(a,b) \perp (c,d)$ then $E \times F$ is an effect algebra {{<cite "foulis1994" >}}.
## tensor product effect algebra
Let $E \times F$ be a product effect algebra. If there exists $E \times F \xrightarrow{\otimes} G$ (called a bimorphism) such that $\forall a:E$ and $\forall b:F$ $F \xrightarrow{\otimes_{a}} G:b \mapsto a \otimes b$ and $E \xrightarrow{\otimes_{b}} G:a \mapsto a \otimes b$ are [[20240703082436]] effect algebra morphisms and $1 \otimes 1 = 1$ then there exists an effect algebra $E \otimes F$ and a bimorphism $E \times F \rightarrow E \otimes F$ such that {{<cite "foulis1994;dvurecenskij2013" 244-246 >}}
1. If $E \times F \xrightarrow{\beta} L$ is a bimorphism, there exists $E \otimes F \xrightarrow{\phi} L$ with $\beta = \phi \circ \otimes$, and
2. $\{p \otimes q: p \in E \wedge q \in F\}$ generartes $E \otimes F$.
### existence
If $E$ and $F$ admit positive sets of probability measures, then there exists $P \otimes Q$.

---

# references
{{< bibliography cited>}}
