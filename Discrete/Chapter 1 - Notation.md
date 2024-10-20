**Subset:**

If $R$ and $S$ are sets, then $R \subseteq S$ means that $R$ is a subset of $S$

**Proper Subset:**

If $R$ and $S$ are sets, then $R \subset S$ means that $R$ is a subset of $S$

**Union:**

Given sets $A$ and $B, A \cup B$ is the union of $A$ and $B$, which is the set consisting of those  elements that are in $A$ or in $B$ (or in both). E.g.,
$$
\{-2,-1,0\} \cup\{0,1,2\}=\{-2,-1,0,1,2\}
$$

**Intersection:**

$A \cap B$ is the intersection of sets $A$ and $B$, which is the set consisting of those elements  that are in both $A$ and $B$. E.g.,
$$
\{-2,-1,0\} \cap\{0,1,2\}=\{0\} ; \text { and }\{-2,-1,0\} \cap \mathbb{N}=\emptyset
$$

**Cartesian Product:**

If $X$ and $Y$ are two sets, their Cartesian product is:
$$
X \times Y=\{(x, y): x \in X \text { and } y \in Y\}
$$
the set of all ordered pairs $(x, y)$ with first component in $X$ and second in $Y$.

Example:

$X=\{1,2,3\}$ and $Y=\{a, b\}$, then the set $X \times Y$ is
$$
\{(1, a),(1, b),(2, a),(2, b),(3, a),(3, b)\}
$$

**Proposition 1.1. Let $X$ and $Y$ be finite sets.**

$|X \times Y|=|X| \times|Y|$.
$\left|X^{n}\right|=|X|^{n}$.

**Problem:** Let $A=\{1,2,3,4,5,6\}$. How many subsets does $A$ have? (Including $A$ itself, and the empty set $\emptyset$ ?)

Idea: to build a subset of $A$, consider each element of $A$ in turn, and declare it either "in" or "out". There are 6 decisions, and each can go two ways, so that's $2^{6}$ possibilities.
$$I=\{0,1\}$$
$$
I^{6}=\left\{\left(a_{1}, \ldots, a_{6}\right): a_{i} \in I\right\}

$$
$$ A=\{1,2,3,4,5,6\}$$
The set of all subsets of $A$ has a bijection with $I^{6}$
$\therefore$  by the definition of a bijection (let $A_S$ be the set of all subsets of $A$)
$$
|I^{6}| = |A_S|
$$
And since we know $$|I^{6}| = |I|^{6} = 2^{6}$$Then
$$
|A_S| = 2^{6} = 64
$$