# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

### PROGRAM

```
import re
str=input()
patterns = 'ab{2,3}?'
if re.search(patterns,  str):
    print("Found a match!")
               
else:
    print("Not matched!")
       
```
### OUTPUT
![image](https://github.com/user-attachments/assets/2a28e16d-9dde-4ac8-84f1-e58e48afd2c7)

### RESULT
Thus the program matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions has been implemented and executed successfully.
