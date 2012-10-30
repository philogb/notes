---
layout: post
title: The Universal Set
permalink: universal-set
categories: [Math, Philosophy]
---

*In von Neumann set theory the universe \\(V\\), which is the class of
all sets, exists. the complement \\(\\sim A\\) of a set \\(A\\) can then be
defined as*

\\(\\sim A = V \\sim A\\).

*But this is not possible in Zermelo-Fraenkel set theory, and it may be
of interest to see why not in some detail. (...) \[For this\] we would need to prove:*

(1) \\((\\exists ! B)(\\forall x)(x \\in B \\leftrightarrow x \\notin A)\\)

*and then we would define complementation by:*

(2) \\(\\sim A = y \\leftrightarrow (\\forall x)(x \\in y \\leftrightarrow x \\notin A)\\ \\&\\ y\\text{ is a set}\\).

*Suppose now that it were possible to prove (1). Let \\(A = \\emptyset \\),
then:*

(3) \\((\\exists ! B)(\\forall x)(x \\in B)\\)

*That is, \\(B\\) is the universal set to which every object belongs;
but with \\(B\\) at hand the axiom schema of separation reduces to the
axiom schema of abstraction by taking \\(A\\) as the universal set
\\(B\\), and Russell's paradox may be derived. We conclude that (1)
cannot be proved and Definition (2) is impossible in Zermelo-Fraenkel
set theory. One aspect of this discussion may be formalized in the
useful result that there does not exist a universal set. As just
indicated, the proof of this theorem proceeds by the line of argument of
Russell's paradox via a reductio ad absurdum*.

*Theorem 41:*  \\((\\nexists A)(\\forall x)(x \\in A)\\)

*(...)*

*Theorem 49:*  \\(\\emptyset = \\{x : x \\not= x\\}\\)

*Proof:*

Suppose there were a \\(y\\) such that

\\(y \\in \\{x : x \\not= x\\}\\)

*then, by theorem 47*

\\(y \\not= y\\)

*which is absurd*.

*Similar to Theorem 41, we also have:*

*Theorem 50:*  \\(\\emptyset = \\{x : x = x\\}\\)

Taken from [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) by Patrick Suppes.

