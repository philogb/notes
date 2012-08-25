---
layout: post
title: Infinite Infinities
permalink: infinite-infinities
categories: [Math, Philosophy]
---

**Is There a Set of Largest Cardinality?**

Till now the largest cardinality we have become acquainted with is that
of the set of points in the line, i.e., the cardinality of the
continuum. Neither the set of points of the square nor the set of points
of the cube has a larger cardinality. Perhaps the cardinality of the
continuum is the largest possible? This turns out not to be the case.
Indeed, there is no set of largest cardinality. Given any set \\(A\\), there
is a set of cardinality greater than the cardinality of \\(A\\). We can
construct it by associating to each point \\(a\\) of a set \\(A\\) the function
\\(f^a(x)\\) assuming the value \\(1\\) at this point and the value \\(0\\) at
the remaining points. Clearly, distinct points give rise to distinct
functions. For example, if set \\(A\\) consists of the points \\(1, 2, 3\\),
then point \\(1\\) corresponds to a function which assumes the value \\(1\\) at
this point, while point \\(2\\) corresponds to a function assuming the value
\\(0\\) at point \\(1\\). These functions are distinct. We take our set \\(B\\) to
be the set of all functions on \\(A\\) with values \\(0\\) and \\(1\\).

Thus, the cardinality of set \\(B\\) is not less than the cardinality of set
\\(A\\). Let us now show that these cardinalities are not equal i.e., no
one-to-one correspondence can be found between the elements of sets \\(A\\)
and \\(B\\). Indeed, suppose such a correspondence existed.

Let us then designate the function corresponding to an element \\(a\\) of
\\(A\\) by \\(f\_a(x)\\). Remember that all the functions \\(f\_a(x)\\)
assume only the two values \\(0\\) and \\(1\\).

Let us define a new function

\\(\\phi(x) = 1 - f\_x(x)\\)

Thus, in order to determine the value of the function \\(\\phi(x)\\) at
some point \\(a\\) of \\(A\\) we first must find the function \\(f\_a(x)\\)
corresponding to this point and subtract its value at \\(x = a\\) from
\\(1\\). It is now clear that the function \\(\\phi(x)\\) is defined on
the set \\(A\\) and assumes only values \\(0\\) and \\(1\\). Consequently,
\\(\\phi(x)\\) is an element of set \\(B\\). But then by our assumption
\\(\\phi(x)\\) corresponds to some point \\(b\\) of \\(A\\); this means that

\\(\\phi(x) = f\_b(x)\\)

It follows from Eqs. (3.32) and (3.33) that for all \\(x\\) in \\(A\\)

\\(1 - f\_x(x) = f\_b(x)\\)

Let us set \\(x = b\\) in this equation. Then we get

\\(1 - f\_b(b) = f\_b(b)\\)

so that

\\(f\_b(b) = \\frac{1}{2}\\)

But this contradicts the requirement that the values of the function
\\(f\_b(x)\\) be \\(0\\) and \\(1\\). The contradiction we have obtained
shows that there can be no one-to-one correspondence between sets \\(A\\)
and \\(B\\).

Thus, given any set \\(A\\), we can construct a set \\(B\\) of larger
cardinality. Therefore, no set of largest cardinality can exist.

*Taken from Stories about Sets by N.Ya.Vilenkin*
