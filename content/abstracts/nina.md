---
speaker: 'Nina Pardal'
title: 'Rewriting consistent answers in annotated databases'
date: '2025-12-01T12:42:17Z'
order: 1
---

In database systems, ensuring that queries return consistent answers in the presence of inconsistency and uncertainty is a key challenge. A foundational approach is to consider *repairs* of the original database —-- minimally modified instances that satisfy the constraints --— and define consistent answers as those that hold across all repairs. In practice, however, databases often carry additional information or metadata, usually incorporated in the form of annotations, which is useful to take into account when reasoning about inconsistent data and obtaining meaningful query answers.

In this talk I will present a logic-based approach to consistent query answering over semiring-annotated databases: rather than returning boolean answers, queries output semiring values that may represent, for example, multiplicity, probabilities, or provenance. This framework allows us to reason about data that is not only inconsistent but also annotated with rich metadata, which is often important to account for in modern data management systems.

The focus will be on naturally ordered positive semirings, and on consistent answers to self-join-free conjunctive queries under key constraints, the most extensively studied setting for consistent query answering on standard databases. I will define the consistent answer to a query, present a variant of first-order logic with semiring semantics, and outline when consistent answers can be captured by a rewriting in this logic, according to the structure of the attack graph of the query. This provides a clean and precise characterisation of rewritability for consistent answers in semiring-annotated databases under key constraints.

