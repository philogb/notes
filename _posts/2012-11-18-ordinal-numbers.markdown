---
layout: post
title: Ordinal Numbers
permalink: ordinal-numbers
categories: [Math, Philosophy]
---

This builds on the [previous article](/notes/cardinal-numbers/). In that article we showed that
we don't really know what cardinal numbers are, but we do know how they
behave. Similarly we showed that Peano's axioms do not define natural
numbers but instead define any kind of progression. In this article
we'll define what a natural number is.

We begin with some description of the classical Cantor theory of ordinal
numbers. This theory depends upon first defining the notion of
*order type* and then designating ordinal numbers as certain special
order types, namely, the order types of well-ordered sets.

Loosely speaking, an order type is the
set of all simply ordered sets which can be put into 1-1 correspondence
with a given simply ordered set such that the order is "preserved".

First let's define what a *simple order structure* is:

\\(\\check{A} = \\langle A, R \\rangle\\) is a *simple order structure* if  and
only if \\(R\\) is a strict simple ordering of \\(A\\).

for example a simple order structure could be \\(\\check{N} = \\langle N, &lt; \\rangle\\) where \\(N\\) are the natural numbers.
In general we use \\(\\omega\\) instead of \\(\\check{N}\\).

Let's define now what it means to be *similar*:

\\(\\check{A} = \\langle A, R \\rangle\\) is *similar under \\(f\\)* to \\(\\check{B} = \\langle B, S \\rangle\\) if  and only if:

 1. \\(f\\) is a 1-1 function.
 2. the domain of \\(f\\) is \\(A\\) and the range of \\(f\\) is \\(B\\).
 3. for every \\(x, y \\in A\\ \\ xRy\\) if and only if \\(f(x)Sf(y)\\).

Then we have that:

\\(\\check{A} = \\langle A, R \\rangle\\) is *similar* to \\(\\check{B} = \\langle B, S \\rangle\\) if and only if there is an \\(f\\) such that \\(\\check{A}\\) is similar under \\(f\\) to \\(\\check{B}\\)

Ok so now we can define an order type in intuitive set theory:

\\(\\tilde{A} = \\{ \\check{B}: \\check{B}\\text{ is similar to }\\check{A}\\}\\)

The difficulty with this is exactly the same we encountered with the
corresponding definition of cardinal numbers: we cannot prove that the
equivalence class \\(\\tilde{A}\\), which is the order type of \\(\\check{A}\\), is not empty. We would have to introduce
an extra axiom similar to the one we showed in the [previous article](/notes/cardinal-numbers/).

In view of the difficulties with definition by abstraction of cardinal
numbers or order types, it is fortunate indeed that for the special case
of ordinal numbers, which are classically order types of well-ordered
sets, a device may be adopted which requires no special axioms to
support it. The idea is to choose just one representative of each order
type which is an ordinal and call this representative *the* ordinal.
That is, in the case of well-orderings we are actually able to construct
a definite example of each possible well-ordering, which we cannot do in
the case of arbitrary orderings. The definite representative we choose
are built up from the empty set:

\\(1 = \\{0\\}\\)

\\(2 = \\{0, \\{0\\}\\} = \\{0, 1\\}\\)

\\(3 = \\{0, \\{0\\}, \\{0, \\{0\\}\\}\\} = \\{0, 1, 2\\}\\)

and so on. Each ordinal has all smaller ordinals as members, and the
membership relation \\(\\in\\) provides the appropriate well-ordering.

More formally, let's define first:

\\( \\varepsilon A = \\{ \\langle x, y \\rangle : x \\in A\\ \\&\\ y \\in A\\ \\&\\ x \\in y \\} \\)

Now let's define what it means to be *complete*:

**\\(A\\) is complete if and only if every member of \\(A\\) is a subset of \\(A\\).**

Finally then

**\\(A\\) is an ordinal if and only if \\(A\\) is complete and
\\(\\varepsilon A\\) connects \\(A\\).**

An interesting fact in ZF about ordinals:

**There is no set \\(A\\) such that for every \\(x, x \\in A\\) if and
only if \\(x\\) is an ordinal.**

The proof consists in showing that if there were such a set, say
\\(A\\), then it would be an ordinal and thus a member of itself,
violating the fact that \\(\\varepsilon A\\) well-orders \\(A\\). That
is, it is absurd to have \\(A \\in A\\).

This theorem shows that in Zermelo set theory the Burali-Forti paradox
of the greatest ordinal is blocked by the fact that the set of all
ordinals does not exist.

Finally we can define the natural numbers by saying:

**\\(A\\) is a natural number if and only if \\(A\\) is an ordinal and
\\(\\widetilde{\\varepsilon A}\\) well-orders \\(A\\)**.

where \\(\\widetilde{\\varepsilon A}\\) is \\(\\{\\langle x, y \\rangle: y\\ \\varepsilon A\\ x\\}\\) and
now we have a proper definition of natural numbers (in ZF).

*Content taken from [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) by Patrick Suppes*

