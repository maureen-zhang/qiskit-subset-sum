# qiskit-subset-sum

A small project for exploring subset sum algorithms using Qiskit and quantum computing techniques.

## Overview

The subset sum problem is classically hard. It was proved NP-complete by Karp (1972) and is a foundational problem in complexity theory.

Knapsack cryptosystems are a direct application of the subset sum problem: they use the hardness of subset sum to build public-key encryption schemes.

## Complexity

- Classical exact solution: O(2^n) in the worst case for an n-element input set.
- Quantum search with Grover's algorithm can reduce brute-force search to roughly O(2^{n/2}).

## Contents

- `README.md` - Project introduction and usage notes
- `src/` - Source code for Qiskit implementation and experiments
- `notebooks/` - Jupyter notebooks for prototyping and analysis

## Getting Started

1. Install Qiskit and required dependencies.
2. Run the provided scripts or notebooks to explore subset sum problem solutions.

## Research Notes

- Subset sum is NP-complete and widely studied in cryptography and quantum algorithms.
- Knapsack-style cryptosystems rely on subset sum hardness and can be broken if the subset sum instance is easy to solve.
- Grover's algorithm offers a quadratic speedup for unstructured search, which can be applied to brute-force subset sum search.

## Proof / Citation

- [citation needed] Karp, R. M. (1972). "Reducibility Among Combinatorial Problems".
- Proof sketch for classical hardness and any quantum speedup should be added in a future revision.
