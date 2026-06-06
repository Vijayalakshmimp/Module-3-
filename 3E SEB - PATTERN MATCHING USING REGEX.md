# Exp.No:3e
## SEB - PATTERN MATCHING USING REGEX

---

### AIM  
o write a Python program to find sequences of Upper case letters joined with a '@'..

---

### ALGORITHM

1. Begin the program.
2. Accept a string 'a' from the user.
3. Define the regular expression pattern as r'[A-Z]+@'.
4. Use the re.search() function to check if the string a is found in the pattern.
5. If a match is found, print "Found a match!".
6. If no match is found, print "Not matched!".
7. Terminate the program.

---

### PROGRAM

```
Reg.No: 212223090030
Name: Vijayalakshmi M P

import re
a=str(input())
pattern=r'[A-Z]+@'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
<img width="1013" height="410" alt="image" src="https://github.com/user-attachments/assets/49d99b4a-d2b8-448f-bbc0-67e5bbe9ee02" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
