---
speaker: 'Axel Ljungström'
title: 'A pain-free formalisation of the Leibniz construction'
date: '2025-12-01T12:42:17Z'
order: 2
---

For better or worse, some mathematicians working in formalisation (including myself) like to work in a proof-relevant setting, such as homotopy type theory. While theorems stated in such a setting enjoy interpretations in a rich class of models, this matters little if we can't prove them in the first place. Indeed, even when proving the most innocent-looking results, there is one recurring issue that often stumps even the most seasoned formaliser: coherences. This talk is about my most recent visit to coherence hell and, in particular, a neat little trick that helped me and my collaborators escape it.

More specifically, this talk concerns an ongoing formalisation project with Tom de Jong and Nicolai Kraus on so-called Leibniz products and exponentials (also known as pushout-products and pullback-powers) and their adjointness. Although this problem is motivated by the development of simplicial type theory, it is also completely self-contained and should be understandable to anyone who knows some basic type theory and/or category theory. The approach we've taken is an instance of a well-known (but, in my experience, sometimes forgotten-about) heuristic for dealing with coherences in general, and my hope is that it will be useful to any mathematician or computer scientist stuck on similar problems.
