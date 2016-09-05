# Rust: Sublist

Write a function to determine if a list is a sublist of another list.

Write a function that given two lists determines if the first list is
contained within the second list, if the second list is contained within
the first list, if both lists are contained within each other or if none
of these are true.

Specifically, a list A is a sublist of list B if by dropping 0 or more elements
from the front of B and 0 or more elements from the back of B you get a list
that's completely equal to A.

Examples:

 * A = [1, 2, 3], B = [1, 2, 3, 4, 5], A is a sublist of B
 * A = [3, 4, 5], B = [1, 2, 3, 4, 5], A is a sublist of B
 * A = [3, 4], B = [1, 2, 3, 4, 5], A is a sublist of B
 * A = [1, 2, 3], B = [1, 2, 3], A is equal to B
 * A = [1, 2, 3, 4, 5], B = [2, 3, 4], A is a superlist of B
 * A = [1, 2, 4], B = [1, 2, 3, 4, 5], A is not a superlist of, sublist of or equal to B

Follow the instructions [here][rust-testing] to run the tests.

[rust-testing]: https://github.com/exercism/xrust/blob/master/docs/TESTS.md

# Source

This exercise is from the [Rust][rust] track on [Exercism][exercism]

[exercism]: http://exercism.io
[rust]: http://exercism.io/languages/rust



