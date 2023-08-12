# Intermediate-Programming-Lab-Activity-1
### Problem
Create a program that will accept the following inputs from the user (use scanner):
- First name
- Last name
- Middle name

Check if the last name and first name  have the same length.

If the length is the same, convert all characters of the last name to an integer by referring
to their alphabet order (e.g. abarro -> 1, 2, 1, 18, 18, 15) and store it in an array. If
the array elements represent a palindrome (e,.g. [1, 2, 2, 2, 1] -> palindrome is [1, 2, 2, 2, 1])
then convert all characters of the middle name to integers by also referring to their alphabet order.
Once done, add the two arrays inside a two-dimensional array (arr [  ] [  ])
and display it to the user in the following format:

```
Outer array = [
                            a1 = [1, 2, 3, 4, 5]
                            a2 = [1, 2, 3, 4, 5]
]
```
Then ask the user to input two numbers that will represent the outer array’s index and the inner array’s
index. Once the user provides the two numbers, display the element and exit the program. If the length
of the last name and first name is not the same, rerun the program and keep track of how many times the
program have been rerun. If the program rerun exceeds 5 times then exit the program on the 6th time.
