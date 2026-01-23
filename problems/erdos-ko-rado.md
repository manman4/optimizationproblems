# Erdős-Ko-Rado Theorem

## Problem Statement

Consider the family of all k-element subsets of an n-element set [n] = {1, 2, ..., n}. A family F of k-subsets is called **intersecting** if every pair of sets in F has at least one element in common (i.e., A ∩ B ≠ ∅ for all A, B ∈ F).

**Question**: What is the maximum size of an intersecting family of k-subsets of [n]?

## Optimal Constant

**Status**: Known (for n ≥ 2k)

**Value**: The maximum size is C(n-1, k-1), where C(n,k) denotes the binomial coefficient "n choose k".

## Current Best Bounds

### Complete Result (n ≥ 2k)

- **Value**: |F| ≤ C(n-1, k-1)
- **Reference**: Erdős, P., Ko, C., & Rado, R. (1961). "Intersection theorems for systems of finite sets". Quarterly Journal of Mathematics.
- **Note**: Equality is achieved by the family of all k-subsets containing a fixed element (e.g., all k-subsets containing the element 1).

### Small Values of n

- **Value**: For n < 2k, the maximum is C(n, k) (the trivial bound: all k-subsets form an intersecting family)
- **Reference**: Observation
- **Note**: When n < 2k, any two k-subsets must intersect by the pigeonhole principle

## History

- **1961**: Erdős, Ko, and Rado prove the theorem for sufficiently large n
- **1973**: Wilson provides a simpler proof
- **1974**: Frankl proves the complete theorem for all n ≥ 2k
- **1975**: Katona gives an elegant proof using the cycle method
- **1984**: Ahlswede and Khachatrian extend to non-uniform hypergraphs

## References

1. Erdős, P., Ko, C., & Rado, R. (1961). "Intersection theorems for systems of finite sets". Quarterly Journal of Mathematics, 12(1), 313-320.
2. Katona, G. O. H. (1972). "A simple proof of the Erdős-Ko-Rado theorem". Journal of Combinatorial Theory, Series B, 13(2), 183-184.
3. Wilson, R. M. (1984). "The exact bound in the Erdős-Ko-Rado theorem". Combinatorica, 4(2-3), 247-257.
4. Ahlswede, R., & Khachatrian, L. H. (1997). "The complete intersection theorem for systems of finite sets". European Journal of Combinatorics, 18(2), 125-136.

## Related Problems

Various generalizations and variants exist:
- Cross-intersecting families
- r-wise intersecting families (every r sets have non-empty intersection)
- Weighted versions with different set sizes

## Notes

The Erdős-Ko-Rado (EKR) theorem is one of the cornerstones of extremal combinatorics. It has inspired an entire field of research on intersection problems.

**Key Extremal Families**:
1. All k-subsets containing a fixed element (the canonical example)
2. For n = 2k, there are other optimal families (e.g., all k-subsets contained in a fixed (2k-1)-subset)

**Modern Developments**:
- The theorem has been extended to many other combinatorial structures
- Algebraic and representation-theoretic proofs provide deeper insights
- Stability results: families that are "almost" as large must be "close" to optimal families

**Applications**:
- Coding theory
- Design theory
- Graph theory (cliques in Kneser graphs)

## Last Updated

2024-01-01 - Initial entry
