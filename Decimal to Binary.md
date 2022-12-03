# Decimal to Binary

## Intro

## Base 10 vs Base 2

## How it works
When converting from base 10 to base 2, you can *"subtract"* values from the decimal value decimal place by decimal place until arriving at a final answer.

## Examples

### Example 1:

Convert decimal value 7 to binary.

4 is the closest value to 7 without going over

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 1 0 0

7 - 4 = 3
 
2 is the closest value to 3 without going over
 
> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 1 1 0
  
7 - 4 - 2 = 1
  
1 is the exact amount we have left, so we will *"subtract"* 1 and will be left with zero left over.

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 1 1 1
 
This means that our new binary number, 0000 0111 has the same value
as our original decimal number

### Example 2:

Convert decimal 233 to binary.

128 is the highest value we can select

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 0 0 0

233 - 128 = 105

64 is the next closest value we can select without going over our remainder

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 0 0 0

233 - 128 - 64 = 41

32 is our next highest option, and it still works for a remainder of 41

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 0 0 0

233 - 128 - 64 - 32 = 9

This time we are going to skip a place and select 8 instead of 16, since 16 > 9

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;1 0 0 0

233 - 128 - 64 - 32 - 8 = 1

We're going to skip a few more places since our remainder is only 1, and select 1 to bring our remainder to 0

> 128 64 32 16 8 4 2 1  
> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;1 0 0 1

233 - 128 - 64 - 32 - 8 - 1 = 0

Thus we are left with a final binary number of

1 1 1 0 1 0 0 1
