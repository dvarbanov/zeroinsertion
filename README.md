# zeroinsertion
Problem 1 - Zero Insertion
The method should return a new String, that is constructed following that rules:

    If two neighboring digits are the same (like 55), insert a 0 between them (505)
    Also, if we add two neighboring digits and take their module by 10 (% 10) and the result is 0 - add 0 between them.

For example, if we have the number 116457, result will be: 10160457:

    1 and 1 are the same, so we insert 0 between them
    6 + 4 % 10 = 0, so we insert 0 between them.
