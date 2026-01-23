# Hardy Inequality

## Problem Statement

Hardy's inequality states that for 1 < p < ∞ and functions u with compact support in (0, ∞), we seek the best constant C such that:

∫₀^∞ |u(x)/x|^p dx ≤ C ∫₀^∞ |u'(x)|^p dx

Similarly, in ℝ^n (n ≥ 3), we have:

∫_{ℝ^n} |u(x)/|x||^p dx ≤ C ∫_{ℝ^n} |∇u(x)|^p dx

## Optimal Constant

**Status**: Known

**Value**: 
- For the one-dimensional case: C_opt = (p/(p-1))^p
- For the n-dimensional case (p = 2): C_opt = ((n-2)/2)^2

## Current Best Bounds

### One-Dimensional Case

- **Value**: C_opt = (p/(p-1))^p
- **Reference**: Hardy, G. H. (1920). "Notes on some points in the integral calculus". Messenger of Mathematics.
- **Note**: This constant is sharp and cannot be improved. Equality is never achieved.

### n-Dimensional Case (p = 2)

- **Value**: C_opt = ((n-2)/2)^2
- **Reference**: Multiple authors, classical result
- **Note**: The inequality fails for n = 1, 2. For n ≥ 3, the constant is sharp.

### General n-Dimensional Case (p ≠ 2)

- **Value**: C_opt = ((n-p)/p)^p
- **Reference**: Various authors in functional analysis literature
- **Note**: Sharp constant for 1 < p < n

## History

- **1920**: Hardy proves the one-dimensional inequality with the sharp constant
- **1930s-1960s**: Extensions to higher dimensions and various function spaces
- **1970s**: Weighted Hardy inequalities developed
- **1980s-present**: Refinements, remainder terms, and Hardy inequalities on manifolds

## References

1. Hardy, G. H. (1920). "Notes on some points in the integral calculus (LX)". Messenger of Mathematics, 54, 150-156.
2. Davies, E. B. (1995). "The Hardy constant". Quarterly Journal of Mathematics, 46(4), 417-431.
3. Kufner, A., Maligranda, L., & Persson, L. E. (2007). "The Hardy Inequality: About its History and Some Related Results". Vydavatelský Servis.

## Related Problems

- [Sobolev Inequality](sobolev-inequality.md)

## Notes

Hardy's inequality is one of the most fundamental inequalities in analysis. Unlike the Sobolev inequality, equality is never achieved in Hardy's inequality - there are no extremizers. However, one can construct sequences of functions for which the ratio approaches the optimal constant.

The inequality has important applications in:
- Spectral theory of differential operators
- Existence theory for elliptic PDEs
- Quantum mechanics (uncertainty principles)

Various improvements and refinements include:
- Remainder terms that quantify how far a function is from violating the inequality
- Weighted versions with different weight functions
- Hardy inequalities on domains and manifolds

## Last Updated

2024-01-01 - Initial entry
