---
layout: post
title: Numbers with non-denumerable decimal expansion 
permalink: numbers-with-non-denumerable-decimal-expansion
categories: [Math, Idea]
---

Crazy Sunday ideas...

Let's consider the interval `[0, 1]` of real numbers. I can pick a
number, say:

        0.25

and create for that number an (ordered) sequence:

        <2, 5>

I can also create a *Power Sequence* (derived from the definition of the
[Power Set](http://en.wikipedia.org/wiki/Power_set)) that for the
previous sequence would give me something like:

        P(<2, 5>) = <<2>, <5>, <2, 5>>

(note that there is no empty set in the new Power Sequence). We
can finally flatten the sequence to obtain:

        <2, 5, 2, 5>

Now all real numbers have a [denumerable](http://en.wikipedia.org/wiki/Denumerable_set)
decimal expansion (i.e. we can create a one-one correspondence between
any sequence of numbers that describe the decimal representation of a number and the sequence
of natural numbers). In our (previous) `0.25` case, we could make it easier by
appending infinite zeros after the number, to obtain:

        <2, 5, 2, 5, 0, 0, ...>

and then build a one-one correspondence with `<1, 2, ...>`.

Ok, let's now consider &prod;/10:

        <3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5, ...>

And now let's take for that decimal expansion the flattened
sequence of it's Power Sequence *P(s)*. We obtain a decimal expansion which
is non-denumerable and which represents a number I'll call:

  &prod;<sub>c</sub>

All real numbers have a representation in this new set of non-denumerable
decimal expansions, just like each integer, rational, etc have a
representation in the [Dedekind (cuts)](http://en.wikipedia.org/wiki/Dedekind_cut)
definition of the real numbers.

It's interesting to note however that this "new set" of "numbers" is a **superset** of the
real numbers, since there is no one-one correspondence between
denumerable and non-denumerable sets, then there is no one-one
correspondence between denumerable sequences and non-denumerable ones.

I think it's a crazy but interesting idea. Some questions and things to
consider:

 * Is this equivalent to a transfinite ordinal theory like the Cantor
   one?
 * I'd like to define a closure with a `|+|` operation in which `P(a)
   |+| P(b) = P(c)` where `a, b, c` belong to **R**. I wonder how that
   would be.

I have plenty of other questions, but I'll just daydream with this until
I find it's a stupid idea.



