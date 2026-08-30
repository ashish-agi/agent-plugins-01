# Subtract

Subtract one or more numbers from a starting value.

## Steps

1. Identify the starting number and the number(s) to subtract, in the order given.
2. Subtract each number from the running total, left to right.
3. Return the final value.

## Edge cases

- Subtracting a negative number: this increases the result (e.g. 5 - (-3) = 8).
- Decimal numbers: keep full precision, don't round unless the user asks.
- Result can be negative — that's a valid answer, not an error.
- Non-numeric input: ask the user to clarify instead of guessing.

## Example

Input: 20 - 8 - 3
Calculation: 20 - 8 = 12, then 12 - 3 = 9
Result: 9
