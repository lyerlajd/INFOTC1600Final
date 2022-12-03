# Decimal to Binary

## Intro

## Base 10 vs Base 2

## How it works
When converting from base 10 to base 2, you can *"subtract"* values from the decimal value decimal place by decimal place until arriving at a final answer.

## Examples

### Example 1:

Convert decimal value 7 to binary.

4 is the closest value to 7 without going over

>128 64 32 16 8 4 2 1
 0   0  0  0 0 1 0 0
 
7 - 4 = 3
 
2 is the closest value to 3 without going over
 
128 64 32 16 8 4 2 1

 0   0  0  0 0 1 1 0
  
7 - 4 - 2 = 1
  
1 is the exact amount we have left, so we will *"subtract"* 1 and will be left with zero left over.
128 64 32 16 8 4 2 1

 0   0  0  0 0 1 1 1
 
This means that our new binary number, 0000 0111 has the same value
as our original decimal number

### Example 2:
