
**2.1) Arrangements**

An **arrangement** (or list or string) is a (finite) sequence of items in which the **order** of the items in the sequence **matters**.

The length of an arrangement is the number of items in the sequence.

**Standard Problem \#1**. How many arrangements of length $k$ can be made from elements of a set $S$ of size $|S|=n$ ?

Solution. $n^{k}$. Why? Each arrangement has $k$ places each of which can be occupied by any one of $n$ entries.

Example. How many 4-letter "words" can be made from the standard A-Z alphabet?
Solution. $26^{4}=456,796$

**Standard Problem $\# 2$**. How many arrangements of length $k$ with no repeats can be made from elements of a set $S$ of size $|S|=n$ ?

Solution. $n(n-1)(n-2) \cdots(n-k+1)=\frac{n!}{(n-k)!}$, provided $k \leq n$.

**2.2) Permutations**

A permutation on a finite set $S$ is an arrangement of length $|S|$ that uses each item from $S$ exactly once.

**Proposition 2.1**. If $|S|=n$, then there are $n$ ! permutations on $S$
Proof. This is Standard Problem \#2 (no repeats) with $n=k$.

**2.3) Counting examples**


Addition principle. Let $A$ and $B$ be two finite sets that are **disjoint**, i.e. $A \cap B=\emptyset$. Then
$$
|A \cup B|=|A|+|B|
$$

More generally, if $A_{1}, A_{2}, \ldots, A_{n}$ are **pairwise disjoint**, meaning that $A_{i} \cap A_{j}=\emptyset$ for all $i \neq j$, then
$$
\left|A_{1} \cup A_{2} \cup \cdots \cup A_{n}\right|=\left|A_{1}\right|+\left|A_{2}\right|+\cdots+\left|A_{n}\right| \text {. }
$$

Example: A card is drawn from a standard deck of 52 playing cards. In how many ways can this card be a heart or diamond?

Solution. The sets $H=\{2 \circlearrowleft, 3 \circlearrowleft, \ldots, \mathrm{~K} \bigcirc\}$ and $D=\{2 \diamond, 3 \diamond, \ldots, \mathrm{~K} \diamond\}$ are disjoint, so $|A \cup D|=|A|+|D|=13+13=26$.