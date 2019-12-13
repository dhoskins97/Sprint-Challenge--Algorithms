#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n log n), the amount of operations is going to be slightly steeper than the amount of inputs as we're comparing squares to cubes, and the higher n becomes, the more operations will be necessary


b) O(n^2), the double loop in this (for and while) means that if we double n, the number of operations will increase exponentially


c) O(n), the amount of operations here is also just n incrementing to 0

## Exercise II

Drop egg from floor 0.5n.
If egg breaks, drop it at 0.25n, if not, at 0.75n
Repeat process of incrementing floor level by half until the correct floor is found

runtime complexity is O(Log(n)), as it's basically just a binary search tree

