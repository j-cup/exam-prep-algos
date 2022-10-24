# Final exam preparation algorithmic exercises

## __1. Sum of Digits / Digital Root__

Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.

## Examples
```
16  -->  1 + 6 = 7
```
```
942  -->  9 + 4 + 2 = 15  -->  1 + 5 = 6
```
```
132189  -->  1 + 3 + 2 + 1 + 8 + 9 = 24  -->  2 + 4 = 6
```
```
493193  -->  4 + 9 + 3 + 1 + 9 + 3 = 29  -->  2 + 9 = 11  -->  1 + 1 = 2
```


## __2. Matrix rotate__

Create a function named rotateMatrix that takes an n×n integer matrix (array of arrays) as parameter and returns a matrix which elements are rotated 90 degrees clockwise.

## Example

### Input:
```
[
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
]
```

### Output:
```
[
  [ 7, 4, 1 ],
  [ 8, 5, 2 ],
  [ 9, 6, 3 ] 
]
```
