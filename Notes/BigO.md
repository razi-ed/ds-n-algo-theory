#Big O Notation
###Time-complexity

- numeric representation of efficiency and performance of a code snippet

- Brings out a generalized, environment independent representation of aptness of an operation

- gives us a picture about how the input affects the runtime algorithm

- most time, it will be used to understsnd worst case

#####Rules

- Constant don't matter [O(10n) -> O(n), O(4n^2) -> O(n^2)]
- Smaller terms don't matter [ O(5n + 2) -> O(n) ]

###Space Complexity

- amount of memory to be allocated for the whole operation

- ***Auxiliary space complexity*** refers to the space required by the algorithm, not including space taken by the input. Generally this is what space complexity refers to

#####Rules

- primitives use constant space

- string uses O(n) space

- reference type also uses O(n) space