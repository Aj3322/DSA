# Question


 (a) An array 'A' contains 25 positive integers. Write an algorithm which finds the number EVNUM of elements of 'A' which are even and the number ODNUM of elements of 'A' which are odd.

 (b) An array 'A' contains 25 positive integers. Write an algorithm which finds all pairs of elements whose sum is 25

### (a) Finding the count of even and odd elements in an array 'A':

```
Input: An array A with 25 positive integers
Output: Number of even (EVNUM) and odd (ODNUM) elements in A

EVNUM = 0 (Initialize count for even numbers)
ODNUM = 0 (Initialize count for odd numbers)

for i = 1 to 25 do
    if A[i] is even then
        increment EVNUM by 1
    else
        increment ODNUM by 1

Output EVNUM, ODNUM (Number of even and odd elements)
```

### (b) Finding all pairs of elements whose sum is 25 in array 'A':

```plaintext
Input: An array A with 25 positive integers
Output: Pairs of elements whose sum is 25

for i = 1 to 25 do
    for j = i+1 to 25 do
        if A[i] + A[j] equals 25 then
            Output A[i], A[j] (Pair found)

Output all pairs found whose sum is 25
```

These algorithms will iterate through the array to count the even and odd elements, and find all pairs of elements that sum up to 25, respectively.

The algebraic expression \( E = (5a+b) \times (3c-d)^3 \) can be represented as a tree structure. To draw the expression tree corresponding to \( E \), let's break it down into its constituent operators and operands.

### Expression Tree for \( E = (5a+b) \times (3c-d)^3 \)

Breaking down the expression into sub-expressions:

- Expression 1: \( 5a+b \)
- Expression 2: \( (3c-d)^3 \)
- Main Expression: Multiply the results of Expression 1 and Expression 2.

#### Expression 1 Tree (5a+b):

```plaintext
         [*]
        /   \
       [+]   [5]
      /   \
     [a]  [b]
```

#### Expression 2 Tree ((3c-d)^3):

```plaintext
        [^]
       /   \
      [-]   [3]
     /   \
    [c]  [d]
```

#### Main Expression Tree (Multiply the results of Expression 1 and Expression 2):

```plaintext
          [*]
         /   \
        [+]   [^]
       /   \   / \
      [a] [b] [-] [3]
              /   \
             [c]  [d]
```


