# Ex.No:4C EXCEPTION HANDLING

## AIM  
To Write a python program for solving the following error using Exception Handling . The rules are ,get the variable 'L' with 3 elements from the user.
use index number '4' for print and clear these error with the statement "check index range" using Exception Handling. 

## ALGORITHM

1. Begin the program.
2. Use eval() to get the list from the user.
3. Use a try block to attempt to print the element at index 4 in the list.
4. If an IndexError occurs (i.e., index 4 is out of range), print "check index range".
5. Terminate the program.

## PROGRAM
```
list=eval(input())
try:
    print(list[4])
except IndexError:
    print("check index range")
```
## OUTPUT
![Screenshot 2025-04-27 163056](https://github.com/user-attachments/assets/2301240a-00bc-476f-a8b1-af9aec155fef)

## RESULT
Thus a python program for solving the following error using Exception Handling for the given set of rules has been successfully implemented.
