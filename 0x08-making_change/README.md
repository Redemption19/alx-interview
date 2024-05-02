# makeChange function

## Description
This Python script contains a function called `makeChange`, which calculates the fewest number of coins needed to meet a given total amount using a provided list of coin denominations.

## Functionality
The `makeChange` function takes two arguments:
- `coins`: A list of integers representing the available coin denominations.
- `total`: An integer representing the total amount for which change needs to be made.

The function returns the fewest number of coins needed to meet the total amount. If the total amount is 0 or less, it returns 0. If the total cannot be met by any combination of coins provided, it returns -1.

## Usage
To use the `makeChange` function in your Python code, import the module containing the function and call it with the appropriate arguments:

```python
from filename import makeChange

coins = [1, 5, 10, 25]
total = 36

result = makeChange(coins, total)
print("Fewest number of coins needed:", result)

