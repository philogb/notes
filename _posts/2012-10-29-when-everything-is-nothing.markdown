---
layout: post
title: Zermelo's fix to Russell's Paradox
permalink: zermelo-fix-russell-paradox
categories: [Math, Philosophy]
---

I started reading [Axiomatic Set Theory](http://www.amazon.com/Axiomatic-Theory-Dover-Books-Mathematics/dp/0486616304/) (AST) by Patrick Suppes. I will
paraphrase some of the content explaining Russell's paradox here, and
will continue (in other articles) to show some of the stuff I've found interesting in his
development of Zermelo-Fraenkel's AST in the book.

In his initial development of set theory, Cantor did not work
explicitly from axioms. However, analysis of his proofs indicates that
almost all of the theorems proved by him can be derived from three
axioms:

 1. The axiom of extensionality for sets, which asserts that two sets are identical if they have the same members
 2. The axiom of abstraction, which states that given any property there exists a set whose members are just those entities having that property
 3. The axiom of choice

The source of trouble is the axiom of abstraction. In 1901
Bertrand Russell discovered that a contradiction could be derived from
this axiom by considering the set of all things which have the property
of not being members of themselves.

We may give a precise formulation of the axiom of abstraction:

\\((\\exists y)(\\forall x)(x\\ \\in\\ y \\leftrightarrow \\phi(x))\\)

To obtain Russell's paradox, we want \\(\\phi(x)\\) to assert that
\\(x\\) is not a member of itself. The appropiate formula is:

\\(x\\ \\notin x\\)

We then have as an instance of the axiom of abstraction:

\\((\\exists y)(\\forall x)(x\\ \\in\\ y \\leftrightarrow x\\ \\notin\\ x)\\)

Taking \\(x = y\\), we infer:

\\(y \\in y \\leftrightarrow y \\notin y\\)

which is logically equivalent to the contradiction:

\\(y \\in y\\ \\&\\ y \\notin y\\)

This simple derivation has far-reaching consequences for the axiomatic
foundations of set theory. It plainly shows that in admitting the
axiom we have granted too much.

The axiom schema used then is due to Enst Zermelo \[1908\]. The precise form of the axiom is:

\\((\\exists y)(\\forall x)(x\\ \\in\\ y \\leftrightarrow x \\in z\\ \\&\\ \\phi(x))\\)

The change is slight but potent. It should be clear that we
cannot create a contradiction from this axiom. Using again the formula \\(x \\notin x\\)
as an instance of this new axiom we have:

\\((\\exists y)(\\forall x)(x\\ \\in\\ y \\leftrightarrow x \\in z\\ \\&\\ (x \\notin x))\\)

and again taking \\(x = y\\) we infer:

\\(y\\ \\in\\ y \\leftrightarrow y \\in z\\ \\&\\ y \\notin y\\)

which is not contradictory. Let's take for example:

\\(A = \\{ \\{1\\}, \\{2\\} \\}\\)

Considering now \\(A\\) and Russell's formula \\(x \\notin x\\) we have:

\\((\\exists y)(y\\ \\in\\ y \\leftrightarrow y \\in A\\ \\&\\ y \\notin y)\\)

The truth of this last formula is seen by taking \\(A\\) itself as an appropiate \\(y\\), for \\(A\\) is
not a member of itself. We get:

\\(A\\ \\in\\ A \\leftrightarrow A \\in A\\ \\&\\ A \\notin A\\)

where both left and right-hand side are false and thus the formula is
not contradictory.


