# Sobolev Inequality

## Problem Statement

The Sobolev inequality concerns the embedding of Sobolev spaces into Lebesgue spaces. For functions in W^{1,p}(ℝ^n) with 1 ≤ p < n, we seek the best constant C such that:

||u||_{L^{p*}(ℝ^n)} ≤ C ||∇u||_{L^p(ℝ^n)}

where p* = np/(n-p) is the Sobolev conjugate exponent.

## Optimal Constant

**Status**: Known

**Value**: The optimal constant is given by:

C_opt = π^{-1/2} n^{-1/p} ((p-1)/(n-p))^{(p-1)/p} [Γ(1 + n/2)Γ(n)/Γ(n/p)Γ(1 + n - n/p)]^{1/n}

For the special case p = 2, this simplifies considerably.

## Current Best Bounds

### Sharp Constant (p = 2)

- **Value**: C_opt = n^{-1/2} (2/n)^{1/2} π^{-1/2} [Γ(n/2)/Γ(n)]^{1/n}
- **Reference**: Talenti, G. (1976). "Best constant in Sobolev inequality". Annali di Matematica Pura ed Applicata.
- **Note**: Extremizers are given by functions of the form (1 + |x|^2)^{(2-n)/2}

### General Case (1 ≤ p < n)

- **Value**: See formula above
- **Reference**: Aubin, T. (1976). "Problèmes isopérimétriques et espaces de Sobolev". Journal of Differential Geometry.
- **Note**: The sharp constant was determined via symmetrization techniques

## History

- **1938**: Sobolev establishes the embedding theorem with some constant
- **1976**: Aubin and independently Talenti determine the sharp constant
- **1980s**: Various extensions to other function spaces and manifolds

## References

1. Talenti, G. (1976). "Best constant in Sobolev inequality". Annali di Matematica Pura ed Applicata, 110(1), 353-372.
2. Aubin, T. (1976). "Problèmes isopérimétriques et espaces de Sobolev". Journal of Differential Geometry, 11(4), 573-598.
3. Lieb, E. H. (1983). "Sharp constants in the Hardy-Littlewood-Sobolev and related inequalities". Annals of Mathematics, 118(2), 349-374.

## Related Problems

- [Hardy Inequality](hardy-inequality.md)

## Notes

The Sobolev inequality is fundamental in the calculus of variations and partial differential equations. The sharp constant and extremizing functions are known explicitly, which is relatively rare for such inequalities.

The inequality fails when p = n (logarithmic Sobolev inequality) and when p > n (Morrey's inequality provides different embedding results).

## Last Updated

2024-01-01 - Initial entry
