---
layout: post
title: Brouwer's Cambridge Lectures on Intuitionism
permalink: brouwers-cambridge-lectures-on-intuitionism
categories: [Math, Philosophy]
---

I started reading *Brouwer's Cambridge lectures on intuitionism*, which
was one of the few books in amazon about intuitionistic mathematics.

It's interesting to read the intuitionistic point of view about the
law of the excluded third:

*The belief in the universal validity of the principle of the excluded third
in mathematics is considered by the intuitionists as a phenomenon of the
history of civilization of the same kind as the former belief in the
rationality of \\(\pi\\), or in the rotation of the firmament about the
earth. The intuitionist tries to explain the long duration of the reign
of this dogma by two facts: firstly that within an arbitrarily given
domain of mathematical entities the non-contradictority of the principle
for a single assertion is easily recognized; secondly that in studying
an extensive group of simple every-day phenomena of the exterior world,
careful application of the whole of classical logic was never found to
lead to error.*

As an example of something not falling within the principle of the
excluded third he introduces first the notion of a fleeing property:

*A fleeing property, assigned to the number \\(n\\), is a property
\\(f\\), which satisfies the following three requirements:*

1. *for each natural number \\(n\\) it can be decided whether or not
   \\(n\\) posseses the property \\(f\\);*
2. *no way of calculating a natural number \\(n\\) possessing \\(f\\) is
   known;*
3. *the assumption that at least one natural number possesses \\(f\\) is
   not known to be an absurdity.*

*Obviously the fleeing nature of a property is not necessarily permanent,
for a natural number possessing \\(f\\) might at some time be found, or
the absurdity of the existence of such a natural number might at some
time be proved.*

*By the critical number \\(\kappa_f\\) of the fleeing property \\(f\\) we
understand the (hypothetical) smallest natural number possessing
\\(f\\). A natural number will be called an up-number of \\(f\\) if it
is not smaller than \\(\kappa_f\\), and a down-number if it is smaller
than \\(\kappa_f\\). Of course, \\(f\\) would cease to be fleeing if an
up-number of \\(f\\) were found.*

*A fleeing property is called two-sided with regard to parity if neither
of an odd nor of an even \\(\kappa_f\\) the absurdity of existence has
been demonstrated.*

*Let \\(s_f\\) be the real number which is the limit
of the infinite sequence \\(a_1, a_2, ..., \\) where \\(a_\nu = (-2)^{-\nu}\\)
if \\(\nu\\) is a down-number and \\(a_\nu = (-2)^{-\kappa_f}\\) if
\\(\nu\\) is an up-number of \\(f\\). This real number violates the
principle of the excluded third, for neither it is equal to zero nor is
it different from zero and, although its irrationality is absurd, it is
not a rational number. Moreover if \\(f\\) is two-sided with regard to
parity then \\(s_f\\) is neither \\(>= 0\\) nor \\(<= 0\\).*

In a sense assuming any of these statements would make \\(f\\) not a fleeing property:

 * If \\(s\_f\\) is \\(0\\) then we know that for all \\(\nu\\) no \\(\nu\\) has the
property \\(f\\), which goes against (3): the assumption that at least one natural
number possesses \\(f\\) is not known to be an absurdity.
 * If \\(s\_f\\) is different than \\(0\\) then we can calculate \\(\kappa\_f\\) but that
goes against (2): no way of calculating a natural number possessing \\(f\\) is known.
 * \\(s\_f\\) cannot be irrational because of how the sequence is defined: \\((-2)^n\\) where n is a whole number.
 * \\(s\_f\\) cannot be rational because we would know \\(a\\) and \\(b\\) of \\(\frac{a}{b}\\) which goes against (2).
 * \\(s\_f\\) cannot be odd or even because it would cease being two-sided with regard to parity.

(I got help [on reddit](http://www.reddit.com/r/PhilosophyofMath/comments/1zxwgt/question_about_intuitionistic_mathematics_taken/)
on this).

The thing is that the point of view in intuitionistic mathematics is
very different than the one in classic mathematics. Take this for
example:

*But now let us pass to infinite systems and ask for instance if there
exists a natural number \\(n\\) such that in the decimal expansion of
\\(\pi\\) the \\(nth, (n+1)th, ..., (n+8)th\\) and \\((n+9)th\\) digits form
a sequence \\(0123456789\\). This question, relating as it does to a so far
not judgeable assertion, can be answered neither affirmatively nor
negatively. But then, from the intuitionistic point of view, because
outside human though there are no mathematical truths, the assertion
that in the decimal expansion of \\(\pi\\) a sequence \\(0123456789\\)
either does or does not occur is devoid of sense.*

Taken from "Brouwer's Cambridge lectures on intuitionism".

