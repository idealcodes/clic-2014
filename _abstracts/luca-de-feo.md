---
layout: abstract
title: Coppersmith's method and generalizations
author: Luca De Feo
affiliation: UVSQ
website: http://defeo.lu/
---

In 1996 a famous
[series of papers by D. Coppersmith](http://scholar.google.fr/scholar?q=coppersmith+rsa&btnG=&hl=en&as_sdt=0%2C5)
introduced a method for finding *small* integer roots of a polynomial
modulo an integer $$N$$ of unknown factorization.  To highlight the
power of his method, Coppersmith presented polynomial-time attacks
against a variety of naive realizations of RSA encryption.

Coppersmith's method encodes the fact of having small roots into a
lattice problem. All coefficients are lifted to $$ℤ$$, and a lattice
is formed so that any root of the original polynomial will also be a
root of any element of the lattice.  After performing an
LLL-reduction, the shortest vector in the reduced basis is such that
any *small* integer root (in $$ℤ$$) is also a root of the original
polynomial modulo $$N$$.

Coppersmith's method has a number of generalization, and it has
[recently been remarked](http://arxiv.org/abs/1008.1284) that its
analogue on function fields is the famous
[Guruswami-Sudan algorithm](http://en.wikipedia.org/wiki/Guruswami%E2%80%93Sudan_list_decoding_algorithm)
for list decoding Reed-Solomon codes.

In this talk we will present the original method by Coppersmith, then
we will skim through the generalizations and links with coding theory.
