# EX 1A Reverse a String
## DATE:22-02-2025
## AIM:
To Write a Program to Create a recursive function to reverse a string

## Algorithm
1. Take input string s.
2. If length of s is 0 or 1, return s (base case).
3. Otherwise, recursively call the function with s[1:].
4. Append s[0] to the result of the recursive call.
5. Return the final reversed string. 

## Program:
```C
/*
Program to implement Reverse a String
Developed by: RAGUL RAAJAN T
Register Number: 212223100043
*/
```
```C

def reverse_string(s):
    """
    Recursive function to reverse a string
    """
    if len(s) <= 1:  # base case: if the string is empty or has only one character, return it as is
        return s
    else:
        return reverse_string(s[1:]) + s[0]  


input_string = input()
reversed_string = reverse_string(input_string)
print(reversed_string) 

```

## Output:

![437666908-7bac129d-03e6-4500-8171-c22addc6f7f2](https://github.com/user-attachments/assets/ee874b35-1201-477e-a09b-78ee4a2d33a0)





## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
