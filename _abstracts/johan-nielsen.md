---
layout: abstract
title:  Fast Decoding of Hermitian Codes Using F[x]-Lattice Basis Reduction
author: Johan Nielsen
website: http://jsrn.dk/
affiliation: INRIA Saclay
---
Joint work with Peter Beelen.

Hermitian codes are a sub-family of Algebraic Geometry codes - a huge family of
evaluation codes defined using function fields over (usually) plane curves.
Hermitian codes have very good minimum distance and can be significantly longer
than Reed-Solomon codes over the same alphabet. Unfortunately, decoding becomes
more complicated, and the best algorithms we know are still asymptotically
slower than those we know for Reed-Solomon codes.

In this talk, I will present the first method which brings the complexity of
decoding Hermitian codes down to O~(n^(5/3)), where n is the length of the code.
We achieve this by embedding the core function field equation into multiple
equations over F[x], F being the base field of the code. The resulting problem
becomes a generalised Padé approximation over F[x], which can be solved by
finding a "short" vector in an explicitly given F[x] lattice. This in turn can
be found using recent methods from algebra, though the notion of "short"
involves some extra difficulties.

Our method applies to two approaches of decoding beyond half the minimum
distance: Guruswami-Sudan and Power decoding. In this talk, however, we will
focus in the embedding into an F[x] problem and therefore discuss only the
decoding up to half the minimum distance (minus half the genus).
