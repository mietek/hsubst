-------------------------------------------------------------------------------

This is an archival copy with minimal updates.  Please see the [original page](https://www.lri.fr/~keller/Recherche/hsubst.html).

-------------------------------------------------------------------------------


# The decidability of the βη-equivalence using hereditary substitutions

Hereditary substitutions are substitutions over the simply typed λ-calculus that **preserve canonical forms** and are **structurally recursive**. This page is devoted to a **formal implementation** of a **normalizer for the simply typed λ-calculus** using hereditary substitutions in [Agda](http://wiki.portal.chalmers.se/agda), which comes with a proof that this normalizer can be use to decide the **decidability of the βη-equivalence**.

- [Sources](#sources)
- [Suggestions and bug report](#suggestions-and-bug-report)

## Sources

The source code is available under the GPL. It is an archive containing:
- A copy of the text version of the GPL.
- The module **hsubst.agda** implements hereditary substitutions for the simply-typed λ-calculus.
- The module **lemmas1.agda** implements operations to work with De Bruijn indices.
- The modules **lemmas2.agda** and **lemmas3.agda** implements basic commutation lemmas.
- The module **lemmas4.agda** implements non trivial commutation lemmas.
- The module **proofs.agda** implements the βη-equivalence and the proofs that hereditary substitutions decide it.
- A **Makefile** to compile it.

Download:
- [Source code](https://www.lri.fr/~keller/Documents-recherche/Stage08/Hereditary-substitution/hsubst.tar.gz)

### Software requirements

For Agda:
- [Agda version 2.2.6](http://code.haskell.org/Agda/Agda-2.2.6.tar.gz)
- [The standard library version 0.3](http://www.cs.nott.ac.uk/~nad/software/lib-0.3.tar.gz)

## Suggestions and bug report

Do not hesitate to make any suggestion or to report bugs to <a href="mailto:keller%20at%20lix%20dot%20polytechnique%20dot%20fr">Chantal Keller</a> (remove the anti-spam dots and at).
