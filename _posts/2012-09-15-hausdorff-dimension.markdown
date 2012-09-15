---
layout: post
title: Fractal Dimension
permalink: hausdorff-dimension
categories: [Math]
---

After the previous post I thought it would be interesting to compare the
topological dimension to the fractal dimension as it is presented in
Kenneth Falconer's [Fractal Geometry](http://www.amazon.com/Fractal-Geometry-Mathematical-Foundations-Applications/dp/0470848626/ref=sr_1_1?ie=UTF8&qid=1347688035&sr=8-1&keywords=kenneth+falconer). A fractal is commonly defined as an object which has
a *Hausdorff-Besicovitch* dimension strictly greater than its topological
dimension.

Quoting from the book:

## Hausdorff measure

Recall that if \\(U\\) is any non-empty subset of n-dimensional
Euclidean space, \\(R^n\\), the *diameter* of \\(U\\) is
defined as \\(|U| = sup\\{|x-y|: x,\\ y\\ \\epsilon\\ U\\}\\), i.e. the
greatest distance apart of any pair of points in \\(U\\). If
\\(\\{U\_i\\}\\) is a countable (or finite) collection of sets of
diameter at most \\(\\delta\\) that cover \\(F\\), i.e. \\(F \\subset \\bigcup\_{i=1}^\\infty\\ U\_i\\)
with \\(0 \\leq |U\_i| \\leq \\delta\\) for each \\(i\\), we say that
\\(\\{U\_i\\}\\) is a \\(\\delta\\)-cover of \\(F\\).

Suppose that \\(F\\) is a subset of \\(R^n\\) and \\(s\\) is a
non-negative number. For any \\(\\delta \\gt 0\\) we define

\\(H\_{\\delta}^s(F) = inf\\left(\\sum\_{i=0}^\\infty |U\_i|^s \\right)\\): \\(\\{U\_i\\}\\) is a \\(\\delta\\)-cover of \\(F\\)

Thus we look at all covers of \\(F\\) by sets of diameter at most
\\(\\delta\\) and seek to minimize the sum of the \\(s\\)th powers of
the diameters. As \\(\\delta\\) decreases, the class of permissible
covers of \\(F\\) is reduced. Therefore, the infimum \\(H\_{\\delta}^s(F)\\) increases,
and so approaches a limit as \\(delta \\to 0\\). We write

\\(H^s(F) = \\lim\_{\\delta \\to 0} H\_{\\delta}^s(F)\\)

This limit exists for any suybset \\(F\\) of \\(R^n\\), though the
limiting value can be (and usually is) \\(0\\) or \\(\\infty\\). We call \\(H^s(F)\\) the *s-dimensional Hausdorff
measure of F*.

(...)

![delta-cover example](/notes/assets/dim/1.png)

## Hausdorff dimension

If \\(t \\gt s\\) and \\(\\{U\_i\\}\\) is a \\(\\delta\\)-cover of
\\(F\\) we have

\\(\\sum\_i |U\_i|^t \\leq \\sum\_i |U\_i|^{t-s} |U\_i|^s \\leq \\delta^{t-s} \\sum\_i |U\_i|^s\\)

so, taking infima, \\(H\_{\\delta}^t(F) \\leq \\delta^{t-s} H\_{\\delta}^s(F)\\). Letting \\(\\delta \\to 0\\)
we see that if \\(H^s(F) \\lt \\infty\\) then \\(H^t(F) = 0\\) for \\(t \\gt s\\).
Thus a graph of \\(H^s(F)\\) against \\(s\\) shows that there is a
critical value of \\(s\\) at which \\(H^s(F)\\) 'jumps' from
\\(\\infty\\) to \\(0\\). This critical value is called the *Hausdorff
dimension* of \\(F\\), and written \\(dim\_H F\\); it is defined for any
set \\(F \\subset R^n\\). (Note that some authors refer to Hausdorff
dimension as *Hausdorff-Besicovitch dimension*). Formally

\\(dim\_H F = inf\\{s \\geq 0\\ :\\ H^s(F) = 0\\} = sup\\{s\\ :\\ H^s(F) = \\infty\\}\\)

![0 to infinity jump plot](/notes/assets/dim/2.png)
