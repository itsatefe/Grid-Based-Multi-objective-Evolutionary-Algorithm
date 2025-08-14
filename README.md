An implementation of the **Adaptive Multi-objective Evolutionary Algorithm based on Grid Subspaces (AGMOEA)**, designed to enhance both convergence and diversity in solving multi-objective optimization problems. This implementation follows the methodology proposed by Li and Wang in their 2021 research.

---

## Overview

AGMOEA integrates a grid-based decomposition of the objective space into subspaces and dynamically allocates evolutionary effort using adaptive selection strategies. Key components include:

- **Subspace dominance ranking** for guided evolution
- **Adaptive selection strategy** to prioritize high-quality subspaces
- **External archive management** for solution elitism and diversity
- **Multiple crossover operators** to balance exploration and exploitation

It is especially useful for tackling complex multi-objective problems where maintaining solution diversity is challenging.

---

## Tech Stack

- **Language:** Python 3.8+
- **Library:** [pymoo](https://pymoo.org/) – A multi-objective optimization framework

---

## Getting Started

No setup is required beyond installing `pymoo`.


## Reference

If you use this code or base your research on this work, please cite the following paper:

> Linlin Li, Xianpeng Wang. "An adaptive multiobjective evolutionary algorithm based on grid subspaces", *Memetic Computing* (2021), 13:249–269.
> [DOI: 10.1007/s12293-021-00336-7](https://doi.org/10.1007/s12293-021-00336-7)

