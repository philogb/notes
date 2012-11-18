---
layout: post
title: Finite Sets
permalink: finite-sets
categories: [Math, Philosophy]
---

*The common sense notion is that a set is finite just when it has
exactly \\(n\\) members for some non-negative integer \\(n\\). If it is
not finite, then it is infinite. This common sense idea is technically
sound and we shall use it subsequently, but it is also intructive to
attempt to find a definition of finitude which does not require explicit
reference to numbers. Such an approach is also intuitively sound since
we continually judge that sets are finite without any clear idea of
their cardinality. (...)*

*Dedekind \[1888\] proposed such a non-numerical definition. A finite set
is one which is not equipollent to any of its proper subsets.
Consideration of simple examples of finite sets suggests that this
definition is intuitively sound. Notice, of course, that we are not
looking for some arbitrary definition of finiteness, but for a
definition which makes exactly those sets finite which are finite in the
sense of having \\(n\\) members for some integer \\(n\\).*

*As sound as Dedekind's definition may seem, it requires the axiom of
choice to prove that every Dedekind finite set is finite in the ordinary
sense. (...)*

*Several other alternative non-numerical definitions of finitude have
been proposed (...). Since Tarski's definition is simple and does not
require the axiom of choice to prove its equivalence to the ordinary
numerical definition, we shall adopt it here. (...)*

*The idea is that a set is finite when any non-empty family of subsets
of the given set has a member of which no other member of the family is
a proper subset. That is, (...) every non-empty family of subsets has a
minimal element with respect to the relation \\(\\subset\\) of being a
proper subset. Formally, we define minimal and maximal elements:*

**Definition 4**

 1. *\\(x\\) is a minimal element of \\(A\\) if and only if \\(x \\in A \\ \\& \\ x \\text{ is a set } \\& \\text{ for every B, if } B \\in A \\text{ then not } B \\subset x\\)*

 2. *\\(x\\) is a maximal element of \\(A\\) if and only if \\(x \\in A \\ \\& \\ x \\text{ is a set } \\& \\text{ for every B, if } B \\in A \\text{ then not } x \\subset B\\)*

*For instance, if:*

\\(A = \\{1, 2, 3\\}\\)

\\(K\_1 = \\{\\{1, 2\\}, \\{1\\}, \\{3\\}\\}\\)

*and*

\\(K\_2 = \\{0, \\{1, 3\\}, A\\}\\)

*Then the sets \\(\\{1\\}\\) and \\(\\{3\\}\\) are minimal elements of
\\(K\_1\\), and the empty set is the minimal element of \\(K\_2\\).
Obviously any other non-empty family of subsets of \\(A\\) has a minimal
element. On the other hand, consider the set of \\(N\\) positive
integers, and consider the family \\(F\\) of subsets \\(\\{N\_1, N\_2, .., N\_n, ...\\}\\) where \\(N\_n\\) is *

\\(N \\sim \\{ 1, 2, ..., n-1 \\}\\)

*Then clearly \\(F\\) has no minimal element, and this situation is typical of infinite sets. The maximal elements of \\(K\_1\\) are \\(\\{1, 2\\}\\) and \\(\\{3\\}\\) and the unique maximal element of \\(K\_2\\) is the set \\(A\\) itself.*

*Tarski's definition, unlike Dedekind's, does not require the notion of equipollence. (...)*

**Definition 5**

*\\(A\\) is finite if and only if every non-empty family of subsets of \\(A\\) has a minimal element.*


Taken from [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) by Patrick Suppes.

