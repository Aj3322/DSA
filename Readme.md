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

Please note that these algorithms provide a basic structure to accomplish the tasks. They can be optimized further based on the specific requirements or the programming language in which you are implementing them.
