# 27-card tensor structure

A tensorial and group-theoretic study of repeated card-dealing procedures,
originating from the 27-card trick and extended to decks of size \(N=b^m\).

The repository investigates how cyclic dealing and pile collection act on
card positions written as digital addresses in base \(b\). This description
leads naturally to tensor products, Kronecker products, permutation matrices
and direct-product group actions.

The current paper develops a general theory of **digitally separable
permutations**: global permutations of \(b^m\) positions whose output digits
depend independently on the corresponding input digits.

Its main results include:

- a positional model for repeated dealing on \(N=b^m\) cards;
- the tensor representation of card positions;
- cyclic rotation of tensor factors during each dealing stage;
- Kronecker factorization of the complete transformation;
- an intrinsic characterization of digitally separable permutations;
- uniqueness of their local permutation factors;
- the faithful embedding
  \[
  S_b^m \hookrightarrow S_{b^m};
  \]
- reconstruction of the local factors from aggregate statistics on digital
  fibers;
- a complete worked example for the 27-card case \(27=3^3\);
- structural consequences for orders, fixed points and conjugacy types;
- a brief comparison with rectangular decks \(N=ij\) and with the
  informational contraction of the classical 21-card trick.

## Paper

The current paper is written in Italian:

**Permutazioni digitalmente separabili nei giochi di carte su \(b^m\)
posizioni — Prodotti di Kronecker e ricostruzione da fibre digitali**

- [PDF version](paper/Articolo.pdf)
- [LaTeX source](paper/Articolo.tex)

The paper is self-contained and focuses on the general mathematical
structure. The 27-card trick is used as the principal concrete example.

## Repository scope

The repository currently contains the mathematical paper and its source.

Planned additions include:

- programs for permutation and tensor analysis;
- exhaustive enumerations of procedures and transformations;
- generated tables and machine-readable datasets;
- computational checks of the theoretical results;
- examples reproducing selected calculations;
- documentation of conventions, file formats and experimental workflows;
- a project overview connecting the paper, software, data and the more
  extensive study from which the repository originated.

The future computational material may include results specific to the
27-card trick that lie outside the scope of the current general paper.

## Project structure

The repository is intended to develop along four connected levels:

1. **Mathematical theory**  
   Positional, tensorial and group-theoretic analysis.

2. **Computational implementation**  
   Programs generating and analysing permutations, procedures and tables.

3. **Data and reproducibility**  
   Generated datasets, exhaustive searches and verifiable examples.

4. **Project synthesis**  
   Documentation explaining how the theoretical and computational parts fit
   together.

## Author

Maurizio Berlanda

## Copyright and licensing

Copyright © 2026 Maurizio Berlanda.

The paper and its LaTeX source are currently provided under standard
copyright protection. No permission for redistribution, modification or
derivative works is granted unless explicitly stated.

Software and datasets added in the future may be distributed under separate
licenses, specified in their respective directories.