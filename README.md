# Range-Expansion
A format for expressing an ordered list of integers is to use a comma separated list of either
  - individual integers
  - Or a range of integers denoted by the starting integer separated from the end integer in the range by a dash, '-'. (The range includes all integers in the interval including both endpoints)
    - The range syntax is to be used only for, and for every range that expands to more than two values.

Example

The list of integers:

-6, -3, -2, -1, 0, 1, 3, 4, 5, 7, 8, 9, 10, 11, 14, 15, 17, 18, 19, 20

Is accurately expressed by the range expression:

-6,-3-1,3-5,7-11,14,15,17-20

(And vice-versa).

The task

Expand the range description:

-6,-3--1,3-5,7-11,14,15,17-20

######Note that the second element above, is the range from minus 3 to minus 1.
