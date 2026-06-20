# qiskit-subset-sum

A small project for exploring subset-sum algorithms using Qiskit and quantum computing techniques.

## Overview

The subset-sum problem is classically hard. It was proved NP-complete by Karp (1972) and is a foundational problem in complexity theory.

Knapsack cryptosystems are a direct application of the subset-sum problem: they use the hardness of subset-sum to build public-key encryption schemes.

## Complexity

- Classical exact solution: $O(2^n)$ in the worst case for an $n$-element input set.
- Quantum search with Grover's algorithm can reduce brute-force search to roughly $O(2^{n/2})$.

## Contents

- `README.md` - Project introduction and usage notes
- `SUBSET_SUM.ipynb` - Jupyter notebook walking through the implementation of Grover's algorithm to solve a given subset-sum problem

## Getting Started

1. Install Qiskit and other required Python dependencies (NumPy, MatPlotLib).
2. Run the provided Jupyter notebook to explore subset-sum problem solutions.

## Research Notes

- Subset sum is NP-complete and widely studied in cryptography and quantum algorithms. See for instance Benoit-Schwartz-Cytron, 'Optimization of a Quantum Subset Sum Oracle' (2024).
- Knapsack-style cryptosystems rely on subset-sum hardness and can be broken if the subset-sum instance is easy to solve.
- Grover's algorithm offers a quadratic speedup for unstructured search, which can be applied to brute-force subset-sum search.

## References

- Benoit, A., Schwartz, S., Cytron, R.K., (2024), Optimization of a Quantum Subset-Sum Oracle, arXiv preprint. [DOI](    
https://doi.org/10.48550/arXiv.2410.01775)
- Karp, R.M. (1972). Reducibility among Combinatorial Problems. In: Miller, R.E., Thatcher, J.W., Bohlinger, J.D. (eds) Complexity of Computer Computations. The IBM Research Symposia Series. Springer, Boston, MA. [DOI](https://doi.org/10.1007/978-1-4684-2001-2_9)

## Future Possibilities

- Proof sketch for classical hardness and any quantum speedup should be added in a future revision.
