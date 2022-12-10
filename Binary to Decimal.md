# Binary to Decimal

## Intro

Converting from binary numbers to decimal numbers.

## How it works
When converting from base 10 to base 2, you are simply adding the value of each binary digit to get a final answer. If the binary number has a 1 in a digit, figure out what that digits decimal value is and add it with the other 1's digits' values.

## Examples

### Example 1:

Convert binary value 0000 0111 to decimal.

> &nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 1 1 1  
> 128 64 32 16 8 4 2 1   
> &nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 4 2 1

0 + 0 + 0 + 0 + 0 + 4 + 2 + 1 = 7

### Example 2:

Convert binary value 1110 1001 to decimal.

> &nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;0 0 0 0  
> 128 64 32 16 8 4 2 1  
> 128&nbsp;64&nbsp;32&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;8 0 0 1

128 + 64 + 32 + 0 + 8 + 0 + 0 + 1 = 233
