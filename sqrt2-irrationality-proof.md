# Proof that √2 is Irrational

**Claim:** √2 is not a rational number (i.e., √2 ∉ ℚ).

## Proof (by contradiction)

Suppose, for contradiction, that √2 is rational. Then it can be written as

    √2 = a / b

for some integers `a` and `b ≠ 0`, where the fraction is in lowest terms —
that is, `gcd(a, b) = 1` (a and b share no common factors).

1. Squaring both sides:

       2 = a² / b²
       a² = 2b²

2. This shows `a²` is even (it equals `2b²`). Since the square of an odd
   integer is always odd, `a` itself must be even. Write `a = 2k` for
   some integer `k`.

3. Substitute back:

       (2k)² = 2b²
       4k² = 2b²
       b² = 2k²

4. This shows `b²` is even, so by the same reasoning, `b` must also be
   even.

5. But now both `a` and `b` are even, which means they share a common
   factor of 2. This contradicts our assumption that `gcd(a, b) = 1`.

Since assuming √2 is rational leads to a contradiction, the assumption
must be false. Therefore:

**√2 is irrational.** ∎

## Notes

- This proof is attributed to the ancient Greeks (the Pythagoreans),
  and is one of the earliest known proofs by contradiction.
- The same argument generalizes: √n is irrational for any positive
  integer n that is not a perfect square.
