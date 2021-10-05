# silq-hhl

A version of the Harrow-Hassidim-Lloyd algorithm implemented in Silq.


## Limitations

- Reverse of a function needs to be declared before it is called
- Change in global state leaks across while loop, which makes it hard to interpret the quantum state. See this issue: https://github.com/eth-sri/silq/issues/29#issue-1015256570

## References

Harrow, A., Hassidim, A., & Lloyd, S. (2009). Quantum Algorithm for Linear Systems of Equations. Phys. Rev. Lett., 103, 150502.
(arXiv https://arxiv.org/abs/0811.3171)

Qiskit tutorial: https://qiskit.org/textbook/ch-applications/hhl_tutorial.html
