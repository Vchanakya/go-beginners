# Data Types

## Null Values

All Go value types come with a so-called "null value" which is the value stored in a variable if no other value is explicitly set.

For example, the following int variable would have a default value of 0 (because 0 is the null value of int, int32 etc):

`var age int // age is 0`

Here's a list of the null values for the different types:

- int => 0
- float64 => 0.0
- string => "" (i.e., an empty string)
- bool => false
