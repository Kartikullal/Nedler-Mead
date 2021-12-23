# Nelder-Mead algorithm

The Nelder-Mead algorithm or simplex search algorithm, originally published in 1965 (Nelder and Mead, 1965), is one of the best known algorithms for multidimensional unconstrained optimization without derivatives. This method should not be confused with Dantzig's simplex method for linear programming, which is completely different, as it solves a linearly constrained linear problem.

The Nelder-Mead algorithm is designed to solve the classical unconstrained optimization problem of minimizing a given nonlinear function f:ℝn→ℝ . The method
* uses only function values at some points in ℝn , and
* does not try to form an approximate gradient at any of these points

## Implementation of Nedler-Mead algorithm in python

There are two python implentations in this repository.

1) Basic implementation:
    This is just a simple implmentation of nedler-mead, by passing vectors as a tuple object, and performing operations inside the nedler-mead function.
    
2) Implemnetation by creating a vector class:
    In this implementation, I have created a vector class, with all the arithmetic functions required inside the class.
