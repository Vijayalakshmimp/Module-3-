# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
Write a Python program to find sequences of Upper case letters joined with a underscore.

---

### ALGORITHM

1. Begin the program.
2. Accept a string a from the user.
3. Define the regular expression pattern as r'[A-Z]+_'.
4. Use the re.search() function to check if the string a is found in the pattern.
5. If a match is found, print "Found a match!".
6. If no match is found, print "Not matched!".
7. Terminate the program.

---

### PROGRAM

```
reg.no: 212223090030
name: Vijayalakshmi M P

import re
a=input()
pattern=r'[A-Z]+_'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="1001" height="337" alt="image" src="https://github.com/user-attachments/assets/1d1394dd-48c4-4462-a371-4cffaf164093" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
