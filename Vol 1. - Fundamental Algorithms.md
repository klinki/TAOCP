Chapter 1
=
1.1 - Algorithms
==
Euclid's algorithm

E1. [Find remainder] Divide m by n and let r be remainder. (0 <= r < n)
E2. [Is it zero?] if r = 0, terminate, n is answer
E3. [Reduce] Set m <- n, n <- r, goto E1.

1. [10]
2. [15]
3. [20]
4. [16]
GCD 2166 and 6099

6099 % 2166 = 1767
2166 % 1767 = 399
1767 % 399 = 171
399 % 171 = 57
171 % 57 = 0, solution is 57.

5. *[12]
1) It might not be finite
2) Non deterministic
4) Uncertain output

6. [20]
7. *[HM21]
8. [M25]
9. *[M30]
