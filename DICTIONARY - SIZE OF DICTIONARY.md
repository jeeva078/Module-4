# Ex.No:4B DICTIONARY - CHECK KEYS IN DICTIONARY

## AIM  
To Write a Python script to check whether a given key  5,9 already exists in a dictionary

## ALGORITHM

1. Begin the program.
2. Define a dictionary d with some key-value pairs.
3. Define the function is_key_present() to check the presence of keys: ,Check if key 5 exists in the dictionary d. If true, print "Key is present in the dictionary".
4. Check if key 9 exists in the dictionary d. If true, print "Key is present in the dictionary".
5. If neither key exists, print "Key is not present in the dictionary".
6. Call the is_key_present() function.
7. Terminate the program.
   
## PROGRAM
```
d = {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}
def is_key_present():
  if 5 in d:
      print('Key is present in the dictionary')
    
  if 9 in d:
       print('Key is present in the dictionary')
      
  else:
      print('Key is not present in the dictionary')
is_key_present()
```
## OUTPUT
![Screenshot 2025-04-27 162344](https://github.com/user-attachments/assets/c3aed88e-066e-4e76-921b-3c9fae65431a)

## RESULT
Thus a Python script to check whether a given key  5,9 already exists in a dictionary has been successfully implemented.
