## Lazy Teacher 

This code is designed to find factor pairs of a given target number and print the pairs whose product is equal to the target number. It includes two functions: `findFactors` and `mainFn`.

The `findFactors` function calculates all the factor pairs of the target number by iterating from 1 up to the square root of the target number. It checks if each number is a factor of the target number and stores the factor pairs in an array.

The `mainFn` function calls the `findFactors` function with a specific target number and then iterates through the factor pairs. It checks if the first factor in each pair is less than or equal to the second factor. if the conditions are met,
 a list of all possible products of two factors that add up to 900900, in ascending order by the first factor, where the first factor should always be smaller than the second factor.

## Usage

To use this code, follow these steps:

1. Call the `findFactors` function and provide the target number as an argument.
2. The `findFactors` function will return an array of factor pairs.
3. Iterate through the factor pairs and check if the first factor is less than or equal to the second factor.
4. If the condition is satisfied, print the factor pair and the target number.
