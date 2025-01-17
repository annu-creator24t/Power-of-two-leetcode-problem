# Power-of-two-leetcode-problem
The **"Power of Two"** problem asks you to determine if a given integer `n` is a power of two. A number is a power of two if it can be expressed as \( 2^k \) where \( k \) is a non-negative integer. For example, 1, 2, 4, 8, etc., are powers of two.

### Key insight:
- A number `n` is a power of two if it has exactly one `1` bit in its binary representation. This can be checked using the condition:
  - \( n > 0 \) and \( n \& (n - 1) = 0 \)

### Example:
- Input: `n = 16` → Output: `true` (because 16 is \( 2^4 \))
- Input: `n = 18` → Output: `false` (because 18 is not a power of two).
