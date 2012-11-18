---
layout: post
title: Thoughts on Cardinal Numbers
permalink: cardinal-numbers
categories: [Math, Philosophy]
---

In [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) Patrick Suppes
introduces a new temporary axiom in order to define cardinal numbers. He
does this because he wants to avoid using the axiom of choice, and also
because he says using the present axioms and the axiom of infinity to
define the *rank* of a set is rather complicated. I quote:

*The special axiom which we introduce requires a new primitive notion,
namely, just that of the cardinal number of a set \\(A\\) (in symbols,
\\(K(A)\\)). The intuitive idea of the axiom should be transparent. We
would like to follow Frege and Russell and define cardinal numbers as
equivalence classes of equipollent sets, but we cannot prove that the
appropriate equivalence classes exist. So we postulate that with each set
\\(A\\) is associated an object \\(K(A)\\), the cardinal number of
\\(A\\), such that with two equipollent sets we associate the same
cardinal number. Notice that on the basis of this axiom and the other
axioms introduced we cannot prove that the cardinal number of a set is
itself a set. Formally, the axiom for cardinal numbers is:*

\\(K(A) = K(B) \\leftrightarrow A \\approx B\\)

It's interesting to see that we're able to define cardinal numbers and deduce
operations on those from this axiom (and others), but we still don't really know what
a cardinal number is. The author has a few thoughts on this that I
quote:

*There is, indeed, a crucial distinction between our construction of the
cardinals and the ordinals. The ordinals are particular, specified sets,
whereas the cardinals are objects which we cannot even classify as sets
or individuals. In this respect our position with respect to the
character of the cardinals is similar to that of the working
mathematician with respect to the natural numbers: he is not concerned
with an explicit definition of the natural numbers in terms of other
known entities, but only with knowning their essential mathematical
properties. In particular, he requires that the natural numbers satisfy
Peano's five axioms, which may be formulated in elementary logic
independent of set theory. These axioms are based on three primitive
symbols: the predicate \\(\\text{is a natural number}\\) the unary operation symbol
\\(\\text{'}\\) for the successor function (intuitively \\(x' = x + 1\\)), and the
individual constant \\(0\\) for the number zero. Peano's axioms are
then:*

 1. \\(0\\) is a natural number.
 2. If \\(x\\) is a natural number then \\(x'\\) is a natural number.
 3. There is no natural number \\(x\\) such that \\(x' = 0\\).
 4. If \\(x\\) and \\(y\\) are natural numbers and \\(x' = y'\\) then \\(x = y\\)
 5. If \\(\\phi(0)\\) and for every natural number \\(x\\) if \\(\\phi(x)\\) then \\(\\phi(x')\\), then for every natural number \\(x\\), \\(\\phi(x)\\).

*It is a proper question and not an idle philosophical speculation to
ask why mathematicians agree almost uniformly on Peano's axioms. Deep
and difficult theorems about the natural numbers were proved before any
adequate axioms were formulated. Putative axioms which did not yield
these theorems would be rejected because, it seems, independent of any
axioms there is a quite precise notion of what is true or false of the
natural numbers. The author is not prepared to give any exact account of
these intuitive notions, and it would be too much of a digression to
examine what other people have said about these matters. But it should
be realized that to say that the natural numbers* **are** *the finite
cardinals or the finite ordinals is not to give such an exact account,
for these intuitive yet precise ideas about the natural numbers are
themselves used in deciding if the proposed identification is
acceptable.*

But are Peano's axioms actually defining natural numbers? Here are some
thoughts Bertrand Russell had on [Introduction to Mathematical
Philosophy](http://www.amazon.com/Introduction-Mathematical-Philosophy-Classic-Reprint/dp/144008047X/ref=sr_1_1?ie=UTF8&qid=1353268720&sr=8-1&keywords=introduction+to+mathematical+philosophy) about this:

*In the first place, Peano's three primitive ideas - namely "\\(0\\)",
"\\(number\\)" and "\\(successor\\)" - are capable of an infinite number of
different interpretations, all of which will satisfy the five primitive
propositions. We will give some examples.*

 1. *Let "\\(0\\)" be taken to mean \\(100\\), and let "\\(number\\)" be taken to mean the numbers from \\(100\\) onward in the series of natural numbers. Then all our primitive propositions are satisfied, even the fourth, for though \\(100\\) is the successor of \\(99\\), \\(99\\) is not a "\\(number\\)" in the sense which we are now giving to the word "\\(number\\)". It is obvious that any number may be substituted for \\(100\\) in this example.*
 2. *Let "\\(0\\)" have its usual meaning, but let "\\(number\\)" mean what we usually call "even numbers", and let the "\\(successor\\)" of a number be what results from adding two to it. Then "\\(1\\)" will stand for number two, "\\(2\\)" will stand for the number four, and so on; the series of "\\(numbers\\)" now will be \\(0, two, four, six, eight, ...\\) All Peano's five premises are satisfied still.*
 3. *Let "\\(0\\)" mean the number \\(1\\), let "\\(number\\)" mean the set \\(1, \\frac{1}{2}, \\frac{1}{4}, \\frac{1}{8}, \\frac{1}{16}, ...\\) and let "\\(successor\\)" mean "half". Then all Peano's five axioms will be true of this set.*

*It is clear that such examples might be multiplied indefinitely. In
fact, given a series \\(x\_0, x\_1, x\_2, x\_3, ..., x\_n, ...\\) which
is endless, contains no repetitions, has a beginning and has no terms
that cannot be reached from the beginning in a finite number of steps,
we have a set of terms verifying Peano's axioms. This is easily seen,
though the formal proof is somewhat long. (...)*

*A series of \[this\] form (...) is called a progression.*

