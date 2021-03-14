---
layout: page
title: Loopless Functional Algorithms
author: jamiesnape
permalink: /publications/msc/
---

## Abstract

*Loopless algorithms* generate successive combinatorial patterns in constant
time, producing the first in time linear to the size of input. Although
originally formulated in an imperative setting, this thesis proposes a
functional interpretation of these algorithms in the lazy language Haskell.
Since it may not be possible to produce a pattern in constant time, a list of
integers generated using the library function `unfoldr` determines the
transitions between consecutive patterns. The generation of Gray codes,
permutations, ideals of posets and combinations illustrate applications of
loopless algorithms in both imperative and functional form, particularly
derivations of the Koda-Ruskey and Johnson-Trotter algorithms. Common themes in
the construction of loopless imperative algorithms, such as focus pointers,
doubly linked lists and coroutines, contrast greatly with the functional uses of
real-time queues, tree traversals, fusion and tupling.

## Full Document

[![Adobe Acrobat Reader Logo](/assets/adobeacrobatreader.png){: height="24" width="24"}](/assets/publications/msc/thesis.pdf) &nbsp; [Thesis](/assets/publications/msc/thesis.pdf)

## Haskell Code

[![GitHub Logo](/assets/github.png){: height="24" width="24"}](https://github.com/snape/Loopless-Functional-Algorithms) &nbsp; [GitHub](https://github.com/snape/Loopless-Functional-Algorithms)

## Citation

Jamie Snape, **Loopless Functional Algorithms**, Master's thesis, Computing Laboratory, University of Oxford, Oxford, UK, 2005, advised by [Richard S. Bird](http://www.cs.ox.ac.uk/people/richard.bird/)

## Copyright

Copyright © 2005 Jamie Snape, Computing Laboratory, University of Oxford. All
rights reserved.

Jamie Snape hereby asserts the moral right to be identified as the author of
*Loopless Functional Algorithms*.

This material is presented to ensure timely dissemination of scholarly and
technical work. Copyright and all rights therein are retained by authors or by
other copyright holders. All persons copying this information are expected to
adhere to the terms and constraints invoked by each author's copyright. In most
cases, these works may not be re-posted without the explicit permission of the
copyright holder.
