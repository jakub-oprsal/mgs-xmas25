---
speaker: 'Ian Shillito'
title: 'Cut elimination via proof search termination'
date: '2025-12-01T12:42:17Z'
order: 3
---



The elimination of the cut rule, a.k.a. cut elimination, is a central result in logic, especially in the part of structural proof theory interested in sequent calculi. Its importance is reflected in the key role it has in the proofs of many core results, including equivalence with axiomatic systems, consistency, and decidability. For the establishment of the latter, a calculus from which cut is eliminated provides a strong foundation for designing decision procedures:  since the cut rule is a major source of non-determinism, its absence greatly simplifies the construction of terminating proof-search algorithms.

In this talk, I will present a reversal in the natural order of things. Rather than making termination of proof-search dependent on cut elimination, I will show how termination itself can be used to establish cut elimination. The underlying method, using the termination measure as inductive parameter for proving cut admissibility, turns out to apply to a wide range of significant systems.
