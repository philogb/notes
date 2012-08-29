---
layout: post
title: Segment and Square
permalink: segment-and-square
categories: [Math, Philosophy]
---

Mathematicians reluctantly reconciled themselves with the fact that
there are as many points on a segment as on an infinite line. But the
following result of Cantor turned out to be even more unexpected.
Searching for a set which would have more points than a segment, he
turned to the set of points of a square. He had no doubt of the result -
after all, the segment occupied in all only one side of the square,
whereas the set of all segments which composed the square had the
cardinality of the continuum.

Cantor searched for three years (from 1871 to 1874) for a proof that it
was impossible to set up a one-to-one correspondence between the points
of the segment and the points of the square.

The years went by, but the desired result could not be obtained. And
then the completely unexpected happened. He succeeded in setting up the
correspondence he believed impossible! He wrote to the mathematician
Dedekind: "I see it, but I don't believe it".

But we have to resign ourselves to the fact that our intuition lets us
down again here - it turn out that there are exactly as many points in
the square as on the segment. A rigorous proof of the statement is made
somewhat complicated by the lack of uniqueness of the decimal expansion
of numbers. We shall therefore present only a sketch of Cantor's proof.

Let us take the segment \\(\[0, 1\]\\) and the square of side \\(1\\) \\(ABCD\\).
We have to set up a one-to-one correspondence between the points of the segment and the
points of the square. Projection of the points of the square onto the
segment \\(AB\\) will not help here; indeed, under projection an
infinite set of points of the square are sent into one point of the
segment (for example, all the points of segment \\(DA\\) go into point
\\(A\\).

We can solve the problem as follows: We can specify any point \\(T\\) of
the square \\(ABCD\\) by means of two numbers, its coordinates \\(x\\)
and \\(y\\) ( or more simply its distances along the sides \\(AB\\) and
\\(AD\\). These numbers can be written as infinite decimals. Since
\\(x\\) and \\(y\\) are not more that \\(1\\), these decimals have the
form

\\(x = 0.\\alpha\_1\\alpha\_2...\\alpha\_n...\\)

\\(y = 0.\\beta\_1\\beta\_2...\\beta\_n...\\)

(for the sake of simplicity we do not take points lying on the sides of
the square, but only take interior points). Here are the decimals of the
numbers \\(x\\) and \\(y\\), for example, if \\(x = 0.63205...\\) and
\\(y = 0.21357...\\) then \\(\\alpha\_1 = 6\\), \\(\\alpha\_2 = 3\\),
\\(\\alpha\_3 = 2\\), etc, and \\(\\beta\_1 = 2\\), \\(\\beta\_2 =
1\\), \\(\\beta\_3 = 3\\), etc.

Now we have to pick the point \\(Q\\) of the segment \\(AB\\) which is
to correspond to \\(T\\). It is enough to say what the length of the
segment \\(AQ\\) is. We choose this length to be equal to the number
\\(z\\), whose decimal expansion is obtained by "shuffling" the decimal
expansions of \\(x\\) and \\(y\\). In other words, we form a third
expansion from the two expansions \[above\] by combining their decimals.

\\(z = 0.\\alpha\_1\\beta\_1\\alpha\_2\\beta\_2\\alpha\_3\\beta\_3...\\alpha\_n\\beta\_n...\\)

For instance, if

\\(x = 0.515623...\\)

and

\\(y = 0.734856...\\)

then we obtain

\\(z = 0.571354682536...\\)

The point \\(z\\) lies on the segment \\(\[0, 1\]\\), and it is clear that
different points of the square correspond to different points of the
segment. Indeed, if points \\(T\\) and \\(T'\\) are not the same, the
the decimal expansion of \\(x\\) and \\(x'\\) or \\(y\\) and \\(y'\\)
must differ at least in one place. But this will lead to a difference in
the decimal expansions of the numbers \\(z\\) and \\(z'\\). A somewhat
more detailed analysis shows that the corresponding points also do not
coincide.

Thus we have set up a one-to-one correspondence between the points of
the square and the points of a part of the segment \\(\[0, 1\]\\). This
shows that the set of points of the square has a cardinality no larger
than that of the set of points of the segment. But its cardinality is
certainly no smaller, so that the cardinalities must coincide.

Not just the square, but the cube as well has only as many points as the
segment. In general, any geometric figure containing at least one line
segment will have just as many points as the segment. Such sets are
called sets with the cardinality of the continuuum. (from the Latin
continuum - unbroken).

*Taken from Stories about Sets by N.Ya.Vilenkin*
