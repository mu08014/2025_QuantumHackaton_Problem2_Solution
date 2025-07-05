# 2025_QuantumHackaton_Problem2_Solution

### Solution for 4th Place – Quantum Hackathon 2025
This repository contains the solution that achieved 4th place in the Quantum Hackathon 2025.

Each Python file can be executed to reproduce the results.

## Method
To solve the problem, we propose a quantum-enhanced approach based on classical graph-solving algorithms. Specifically, we utilize three stages of the Quantum Approximate Optimization Algorithm (QAOA):

* First QAOA determines the overall graph shape.

* Second QAOA estimates the edges for each shape.

* Third QAOA infers specific edges that satisfy additional constraints, using the subgraph derived from the second QAOA.

To facilitate convergence, we incorporate Dicke states and classical optimization techniques. Moreover, to ensure feasibility on NISQ devices, we apply error mitigation strategies. For detailed methodology, please refer to the attached file: [Instant_Insanity_puzzle_KHUbit.pdf](https://github.com/mu08014/2025_QuantumHackaton_Problem2_Solution/blob/main/Instant%20Insanity%20puzzle_KHUbit.pdf)] (Instant_Insanity_puzzle_KHUbit.pdf)
