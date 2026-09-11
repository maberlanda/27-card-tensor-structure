# 27-card tensor structure

A tensorial and group-theoretic study of repeated card-dealing procedures,
originating from the 27-card trick and extended to decks of size \$N=b^m\$.

The repository investigates how cyclic dealing and pile collection act on
card positions written as digital addresses in base \$b\$. This description
leads naturally to tensor products, Kronecker products, permutation matrices
and direct-product group actions.

The current paper develops a general theory of **digitally separable
permutations**: global permutations of \$b^m\$ positions whose output digits
depend independently on the corresponding input digits.

Its main results include:

- a positional model for repeated dealing on \$N=b^m\$ cards;
- the tensor representation of card positions;
- cyclic rotation of tensor factors during each dealing stage;
- Kronecker factorization of the complete transformation;
- an intrinsic characterization of digitally separable permutations;
- uniqueness of their local permutation factors;
- the faithful embedding $S_b^m \hookrightarrow S_{b^m}$;
- reconstruction of the local factors from aggregate statistics on digital
  fibers;
- a complete worked example for the 27-card case \$27=3^3\$;
- structural consequences for orders, fixed points and conjugacy types;
- a brief comparison with rectangular decks \$N=ij\$ and with the
  informational contraction of the classical 21-card trick.

## Paper

The current paper is written in Italian:

**Permutazioni digitalmente separabili nei giochi di carte su \$b^m\$
posizioni — Prodotti di Kronecker e ricostruzione da fibre digitali**

- [PDF version](paper/Articolo.pdf)
- [LaTeX source](paper/Articolo.tex)

The paper is self-contained and focuses on the general mathematical
structure. The 27-card trick is used as the principal concrete example.

## Repository scope

This repository is devoted to the mathematical paper and material that
directly supports it, including its LaTeX source, reproducible calculations
and supplementary examples.

The companion software is maintained as a separate project.

## Companion software

The structures discussed in the paper can also be explored computationally with:

**27-Card Trick Explorer**

https://github.com/maberlanda/27-card-trick-explorer

## Author

Maurizio Berlanda

## Copyright and licensing

Copyright © 2026 Maurizio Berlanda.

The paper and its LaTeX source are currently provided under standard
copyright protection. No permission for redistribution, modification or
derivative works is granted unless explicitly stated.

Supplementary datasets or other material added to this repository may be
distributed under separate licenses, specified where applicable.