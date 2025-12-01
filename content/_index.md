---
title: 'MGS Christmas Seminar 2025'
date: 2025-11-23T13:44:05+00:00
---

#### University of Birmingham, Tuesday 16 December 2025

The [Midlands Graduate School](https://www.cs.nott.ac.uk/MGS/) (MGS) is an annual spring graduate school on the mathematical foundations of computing science. It has run annually since 1999 and has been held at either the University of Birmingham, the University of Leicester, the University of Nottingham, or at the University of Sheffield.

The school is aimed at graduate students, typically in their first or second year of study for a PhD, but the school is open to anyone who is interested in learning more about mathematical computing foundations, and all such applicants are warmly welcomed. We very much encourage learners from abroad and from industry to attend, and many have done so in the past. The next MGS spring school will be held at the University of Nottingham, 13–17 April 2026.

In addition to the spring school, the MGS has an afternoon of Christmas seminars.
Participation at the Christmas seminar is free to all, and no registration is required.

## Speakers

- [Nina Pardal](https://glyc.dc.uba.ar/nina/) (Edinburgh)  
  *Rewriting consistent answers in annotated databases*
- [Axel Ljungström](https://aljungstrom.github.io) (Nottingham)  
  *A pain-free formalisation of the Leibniz construction*
- Ian Shillito (Birmingham)

Talks will run **from 2pm to 5.15pm**. Afterwards, we will continue to a pub and dinner (details TBA).

## Schedule

(TBA)

## Abstracts

### Nina Pardal - *Rewriting consistent answers in annotated databases*

In database systems, ensuring that queries return consistent answers in the presence of inconsistency and uncertainty is a key challenge. A foundational approach is to consider *repairs* of the original database —-- minimally modified instances that satisfy the constraints --— and define consistent answers as those that hold across all repairs. In practice, however, databases often carry additional information or metadata, usually incorporated in the form of annotations, which is useful to take into account when reasoning about inconsistent data and obtaining meaningful query answers.

In this talk I will present a logic-based approach to consistent query answering over semiring-annotated databases: rather than returning boolean answers, queries output semiring values that may represent, for example, multiplicity, probabilities, or provenance. This framework allows us to reason about data that is not only inconsistent but also annotated with rich metadata, which is often important to account for in modern data management systems.

The focus will be on naturally ordered positive semirings, and on consistent answers to self-join-free conjunctive queries under key constraints, the most extensively studied setting for consistent query answering on standard databases. I will define the consistent answer to a query, present a variant of first-order logic with semiring semantics, and outline when consistent answers can be captured by a rewriting in this logic, according to the structure of the attack graph of the query. This provides a clean and precise characterisation of rewritability for consistent answers in semiring-annotated databases under key constraints.

### Axel Ljungström - *A pain-free formalisation of the Leibniz construction*

For better or worse, some mathematicians working in formalisation (including myself) like to work in a proof-relevant setting, such as homotopy type theory. While theorems stated in such a setting enjoy interpretations in a rich class of models, this matters little if we can't prove them in the first place. Indeed, even when proving the most innocent-looking results, there is one recurring issue that often stumps even the most seasoned formaliser: coherences. This talk is about my most recent visit to coherence hell and, in particular, a neat little trick that helped me and my collaborators escape it.

More specifically, this talk concerns an ongoing formalisation project with Tom de Jong and Nicolai Kraus on so-called Leibniz products and exponentials (also known as pushout-products and pullback-powers) and their adjointness. Although this problem is motivated by the development of simplicial type theory, it is also completely self-contained and should be understandable to anyone who knows some basic type theory and/or category theory. The approach we've taken is an instance of a well-known (but, in my experience, sometimes forgotten-about) heuristic for dealing with coherences in general, and my hope is that it will be useful to any mathematician or computer scientist stuck on similar problems.

## Local organisers

- Sean Moss
- Jakub Opršal

Any queries should be addressed to [Sean Moss](mailto:s.k.moss@bham.ac.uk).
