# Population Growth Code Challenge

## Problem Statement

In a small town, the population at the beginning of a year is `p0`. The population regularly increases by a fixed percentage `percent` per year, and additionally, a certain number of new inhabitants `aug` come to live in the town each year. The objective is to calculate the number of entire years needed for the town's population to become greater than or equal to a given value `p`.

## Function Signature

```javascript
function nbYear(p0, percent, aug, p)
```

## Parameters

- `p0` (integer): The initial population of the town.
- `percent` (float): The annual percentage increase in population (as a decimal).
- `aug` (integer): The number of inhabitants coming or leaving each year.
- `p` (integer): The population the town needs to surpass.

## Output

- The function `nbYear` should return the number of entire years needed to reach or surpass the given population `p`.

## Examples

```javascript
nbYear(1000, 2, 50, 1200);
// Output: 3
// Explanation: At the end of the first year, there will be 1070 inhabitants.
// At the end of the second year, there will be 1141 inhabitants.
// At the end of the third year, there will be 1213 inhabitants, which is greater than or equal to 1200.

nbYear(1500, 5, 100, 5000);
// Output: 15

nbYear(1500000, 2.5, 10000, 2000000);
// Output: 10
```

## How to Use

1. Copy the `nbYear` function and paste it into your JavaScript environment or file.
2. Call the `nbYear` function with the required arguments: `p0`, `percent`, `aug`, and `p`.
3. The function will return the number of entire years needed to reach or surpass the given population `p`.

## Constraints

- All input parameters are positive integers (`p0`, `aug`, and `p`) or positive or non-negative floating-point numbers (`percent`).
- The function is expected to handle valid inputs, so no additional input validation is necessary in this context.

## Contributing

If you find any issues or have improvements to suggest, feel free to submit a pull request or create an issue in the repository.

## License

This code is licensed under the MIT License. You are free to use, modify, and distribute it for personal and commercial purposes. 

