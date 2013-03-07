---
layout: post
title: The Analog Procedure
permalink: analog-computers
categories: [Reading]
---

##The Analog Procedure

*In an analog machine each number is represented by a suitable physical
quantity, whose values, measured in some pre-assigned unit, is equal to
the number in question. This quantity may be the angle by which a
certain disk has rotated, or the strength of a certain current, or the
amount of a certain (relative) voltage, etc. To enable the machine to
compute, i.e. to operate on these numbers according to a predetermined
plan, it is necessary to provide organs (or components) that can perform
on these representative quantities the basic operations of mathematics.*

###The Conventional Basic Operations

*These basic operations are usually understood to be the "four species of
arithmetic": addition (the operation \\(x + y\\)), subtraction  \\((x -
y)\\), multiplication \\((xy)\\), division \\((x / y)\\).*

*Thus it is obviously not difficult to add or to subtract two currents
(by merging them in parallel or in antiparallel directions).
Multiplication (of two currents) is more difficult, but there exist
various kinds of electrical componentry which will perform this
operation. The same is true for division (of one current by another).
(For multiplication as well as for division - but not for addition and
subtraction - of course the unit in which the current is measured is
relevant).*

###Unusual Basic Operations

*A rather remarkable attribute of some analog machines, on which I will
have to comment a good deal further, is this. Occasionally the machine
is built around other "basic" operations than the four species of
arithmetic mentioned above. Thus the classical "differential analyzer",
which expresses numbers by the angles by which certain disks have
rotated, proceeds as follows. Instead of addition, \\(x + y\\), and
subtraction, \\(x - y\\), the operations \\(\\frac{x + y}{2}\\) and
\\(\\frac{x - y}{2}\\) are offered, because a readily available simple
component, the "differential gear" (the same one that is used on the
back axle of an automobile) produces these. Instead of multiplication,
\\(xy\\), an entirely different procedure is used: In the differential
analyzer all quantities appear as functions of time, and the
differential analyzer makes use of an organ called the "integrator",
which will, for two such quantities \\(x(t), y(t)\\) form the
("Stieltjes") integral \\(z(t) = \\int^t x(t) dy(t)\\).*

*The point in this scheme is threefold:*

*First: the three above operations will, in suitable combinations,
reproduce three of the four usual basic operations, namely addition,
subtraction and multiplication.*

*Second: in combination with certain "feedback" tricks, they will also
generate the fourth operation, division. I will not discuss the feedback
principle here, except by saying that while it has the appearance of a
device for solving implicit relations, it is in reality a particularly
elegant short-circuited iteration and successive approximation scheme.*

*Third, and this is the true justification of the differential
analyzer: its basic operations \\(\\frac{x + y}{2}\\),
\\(\\frac{x - y}{2}\\) and integration are, for wide classes of problems,
more economical than the arithmetic ones \\(x + y,\\ x - y,\\ xy,\\ x / y\\).
More specifically: any computing machine that is to solve a complex
mathematical problem must be "programmed" for this task. This means that
the complex operation of solving that problem must be replaced by a
combination of the basic operations of the machine. Frequently it means
something even more subtle: approximation of that operation - to any
desired (prescribed) degree - by such combinations. Now for a given
class of problems one set of basic operations may be more efficient,
i.e. allow the use of simpler, less extensive, combinations than another
such set. Thus, in particular, for systems of total differential
equations - for which the differential analyzer was primarily designed -
the above mentioned basic operations of that machine are more efficient
than the previously mentioned arithmetical basic operations  \\(x + y,\\ x - y,\\ xy,\\ x / y\\).*

Taken from *The Computer and the Brain* by *John von Neumann*.


