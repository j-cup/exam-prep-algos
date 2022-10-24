# Final exam preparation algorithmic exercises

## __1. Sum of Digits / Digital Root__

Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.

### Examples
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

### Example

#### Input:
```
[
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
]
```

#### Output:
```
[
  [ 7, 4, 1 ],
  [ 8, 5, 2 ],
  [ 9, 6, 3 ] 
]
```


## __3. Killing time in Cartesia__

You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.

Note: you will always receive a valid array containing a random assortment of direction letters ('n', 's', 'e', or 'w' only). It will never give you an empty array (that's not a walk, that's standing still!).

### Example
```
['n','n','e', 's', 'w', 's']  -->  false
```

```
['n', 'w', 'n', 'e', 's', 's', 'w', 'n', 'e', 's']  -->  true
```

## __4. Pangram__

A pangram is a sentence that contains every single letter of the alphabet at least once. For example, the sentence "The quick brown fox jumps over the lazy dog" is a pangram, because it uses the letters A-Z at least once (case is irrelevant).
Given a string, detect whether or not it is a pangram. Return True if it is, False if not. Ignore numbers and punctuation.

### Example
```
"Mr. Jock, TV quiz PhD., bags few lynx."  -->  true
```

```
"Alphabet is cool"  -->  false
```

## __5. Which are in?__ [[CW-6](https://www.codewars.com/kata/550554fd08b86f84fe000a58)]

Given two arrays of strings a1 and a2 return a sorted array r in lexicographical order of the strings of a1 which are substrings of strings of a2.

Notes: Arrays are written in "general" notation. See "Your Test Cases" for examples in your language. In Shell bash a1 and a2 are strings. The return is a string where words are separated by commas. Beware: r must be without duplicates.

### Example
#### Input:
```
a1 = ["arp", "live", "strong"]
a2 = ["lively", "alive", "harp", "sharp", "armstrong"]
```

#### Output:
```
["arp", "live", "strong"]
```

### Input:
```
a1 = ["tarp", "mice", "bull"]
a2 = ["lively", "alive", "harp", "sharp", "armstrong"]
```

### Output:
```
[]
```


## __6. Replace With Alphabet Position__ [[CW-6](https://www.codewars.com/kata/546f922b54af40e1e90001da)]

In this kata you are required to, given a string, replace every letter with its position in the alphabet. If anything in the text isn't a letter, ignore it and don't return it. `"a" = 1, "b" = 2` 

Note: we do not differentiate between lowercase and uppercase.

### Example
#### Input:
```
alphabetPosition("The sunset sets at twelve o' clock.")
```

#### Output:
```
"20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11"
```

## __7. Who likes it?__ [[CW-6](https://www.codewars.com/kata/5266876b8f4bf2da9b000362)]

You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.
Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:

### Example
```
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```


## __. XXX__

xxx

## Example
```
xxx
```
