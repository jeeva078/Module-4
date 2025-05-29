# Ex.No:4D FILES - FREQUENCY OF CHARACTERS IN A FILE

## AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

## ALGORITHM

1. Begin the program.  
2. Define the function `create_file()` that accepts two arguments:  
   - `file_path`: The path to the file.  
   - `content`: The string content to be written into the file.  
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.  
4. Close the file (this is automatically done when exiting the `with` block).  
5. Define the function `character_frequency()` that accepts one argument:  
   - `file_path`: The path to the file whose character frequency is to be calculated.  
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.  
7. Initialize an empty dictionary (`d1`) to store the frequency of each character using `defaultdict(int)`.  
8. Loop through each character in the `content`:  
   - For each character `ch`, increment its corresponding frequency in the dictionary `d1`.  
9. Return the dictionary `d1`, which contains the frequency of each character in the file.  
10. Terminate the program.

---

## PROGRAM
```
from collections import defaultdict

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to calculate character frequencies
def char_frequency(file_path):
   char_count=defaultdict(int)
   with open(file_path,'r')as file:
       for line in file:
           for char in line:
               char_count[char]+=1
   return char_count
file_path="example.txt"
file_content="saveetha engineering college"
create_file(file_path,file_content)
```

## OUTPUT
![Screenshot 2025-04-27 163438](https://github.com/user-attachments/assets/efaf4a5e-f1c3-411d-9b8b-1e600af9e532)
![Screenshot 2025-04-27 163447](https://github.com/user-attachments/assets/998203bd-d7bf-4b97-ad2a-832ae836cc43)
![Screenshot 2025-04-27 163456](https://github.com/user-attachments/assets/d1854316-855f-44bd-bcd1-36a0a3824887)
![Screenshot 2025-04-27 163505](https://github.com/user-attachments/assets/eca316e4-6530-4fb1-8274-532fb19076d9)

## RESULT
Thus a Python program that reads a file and counts the frequency of each character in it has been successfully implemented.
