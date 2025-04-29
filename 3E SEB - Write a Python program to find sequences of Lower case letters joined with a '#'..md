# Exp.No:3e
## SEB - Write a Python program to find sequences of Lower case letters joined with a '#'.


### AIM  
To write a Python program to find sequences of Lower case letters joined with a '#'.


### ALGORITHM

Start

Import the re module (regular expressions)

Input a string s from the user

Use re.fullmatch() to check if s matches the pattern:
'[a-z]*#+[a-z]+'
This pattern means:

Zero or more lowercase letters ([a-z]*)

One or more # characters (#+)

One or more lowercase letters again ([a-z]+)

If the pattern matches:

Print "Found a match!"

Else:

Print "Not matched!"

End
### PROGRAM
import re

s=input()

if re.fullmatch(r'[a-z]*#+[a-z]+',s):

    print("Found a match!")
else:

    print("Not matched!")

### OUTPUT
![image](https://github.com/user-attachments/assets/41e456c6-c454-4edd-ada5-34da6a24d2bb)


### RESULT
Thus, program to find sequences of Lower case letters joined with a '#', was implemented successfully. 

