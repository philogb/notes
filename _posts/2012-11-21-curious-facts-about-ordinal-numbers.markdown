---
layout: post
title: Curious Facts about Ordinal Numbers
permalink: curious-facts-about-ordinal-numbers
categories: [Math, Philosophy]
---

This builds on [previous notes](/notes/ordinal-numbers). Some cool facts
about ordinals:

### The addition of ordinal numbers is not commutative.

We have the following definition for addition on ordinal numbers:

(i) \\(\alpha + 0 = \alpha\\)

(ii) \\(\alpha + \beta' = (\alpha + \beta)'\\)

(iii) if \\(\beta\\) is a limit ordinal then \\(\alpha + \beta = \bigcup\_{\gamma \in \beta}(\alpha + \gamma)\\)

It's easy to see that addition is not commutative with this example:

\\(1 + \\omega \\neq \\omega + 1\\)

Starting from the left side we have that:

\\(1 + \\omega = \bigcup\_{\gamma \in \omega}(1 + \gamma)\\) which expands to:

\\(1 \\cup 2 \\cup 3 \\cup ... = \\{0\\} \\cup \\{0, 1\\} \\cup \\{0, 1, 2\\} \\cup ... = \\omega\\)

On the right side we have:

\\(\\omega + 1 = (\\omega + 0)' = \\omega' = \\omega \\cup \\{\\omega\\}\\)

and \\(\\omega \\neq \\omega'\\) simply because \\(\\omega \\in \\omega'\\) and
following the ordinal definition \\(\\omega \\notin \\omega\\).


### Ordinal multiplication is not distributive from the right

We have the following definition for multiplication on ordinal numbers:

(i) \\(\alpha . 0 = 0\\)

(ii) \\(\alpha . \beta' = \alpha . \beta + \alpha\\)

(iii) if \\(\beta\\) is a limit ordinal then \\(\alpha . \beta = \bigcup\_{\gamma \in \beta}(\alpha . \gamma)\\)

It's easy to see that multiplication is not distributive from the right with this example:

\\((1 + 1)\\omega \\neq 1 . \\omega + 1 . \\omega\\)

On the left side of the equation we have:

\\((1 + 1) . \\omega = 2 . \\omega\\) and we can use (iii) to get

\\(2 . \\omega = \bigcup\_{\gamma \in \omega}(2 . \gamma)\\) which
expanded looks like:

\\((2 . 1) \\cup (2 . 2) \\cup (2 . 3) \\cup ...\\) which is:

\\(\\{0, 1\\} \\cup \\{0, 1, 2, 3\\} \\cup \\{0, 1, 2, 3, 4, 5\\} \\cup ... = \\omega\\)

On the right hand side we have:

\\(1 . \\omega + 1 . \\omega = \\omega + \\omega > \\omega\\) which also
means that:

\\(\\omega + \\omega \\neq \\omega\\)

### The exponent rule is not always true

We have the following definition for exponentiation on ordinal numbers:

(i) \\(\alpha^0 = 1\\)

(ii) \\(\alpha^{\beta'} = \alpha^\beta . \alpha\\)

(iii) if \\(\beta\\) is a limit ordinal and \\(\alpha \> 0\\) then \\(\alpha^\beta = \bigcup\_{\gamma \in \beta}(\alpha^\gamma)\\)

(iv) if \\(\beta\\) is a limit ordinal and \\(\alpha = 0\\) then \\(\alpha^\beta = 0\\)

Let's try to see the counterexample:

\\((\omega . 2)^2 \neq \omega^2 . 2^2\\)

If we start from the right side we have:

\\(\omega^2 . 2^2 = \omega^2 . 4 = \omega^2 . 3 + \omega^2 = \omega^2 . 2 + \omega^2 + \omega^2\\) and if we
continue the expansion we have:

\\(\omega^2 + \omega^2 + \omega^2 + \omega^2 \> \omega^2 + \omega^2\\) so
we know that:

\\(\omega^2 + \omega^2 + \omega^2 + \omega^2 \neq \omega^2 + \omega^2\\)
let's call this (1).

If we expand the left side we get:

\\((\omega . 2)^2 = (\omega . 2) . (\omega . 2)\\) since the product of
ordinals is associative we can do:

\\(\omega . (2 . \omega) . 2\\) let's call this equation (2).

If we expand the product \\(2 . \omega\\) we get:

\\(2 . \omega = \bigcup\_{\gamma \in \omega}(2 . \gamma)\\) which
expands to:

\\((2 . 1) \\cup (2 . 2) \\cup (2 . 3) \\cup ... = \omega\\). Going back
to (2) we now have:

\\(\omega . (2 . \omega) . 2 = \omega . \omega . 2 = \omega^2 . 2 = \omega^2 + \omega^2\\)
and by (1) we know this is different to the right hand side.


### Things that are undefined in analysis have a clear meaning for ordinals

This might be arguably the coolest thing.
So for example \\(0^0, \infty^0, 1^\infty\\) have clear meanings:

\\(0^0 = \omega^0 = \alpha^0 = 1\\)

and

\\(1^\omega = 1^\beta = 1\\)



*Content taken from [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) by Patrick Suppes*


