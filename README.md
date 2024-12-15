# Julia Integer Overflow Edge Case

This repository demonstrates a potential integer overflow issue in Julia. The `myfunction` function calculates the square of a number, handling positive, zero, and negative inputs. However, for extremely large integer inputs, an overflow could lead to unexpected results.

The provided solution demonstrates how to mitigate this by using arbitrary-precision integers.