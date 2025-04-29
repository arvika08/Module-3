# Exp.No:3a
## STRING - Complete the  python program to count the vowels of a given string.

### AIM  
To write a python program to count the vowels of a given string.

### ALGORITHM

Start

Declare a string variable str

Input a string from the user and store it in str

Create a dictionary vow with keys 'a', 'e', 'i', 'o', 'u', all initialized to 0

Set a flag variable to False

For each character i in the string str:

If i is a key in vow:

Increment vow[i] by 1

Set flag = True

After the loop:

If flag is still False, print "There are no vowels in [str]"

Else, for each vowel in the dictionary:

If the count is greater than 0, print the vowel and its count

End

### PROGRAM
str=input()

vow={'a':0,'e':0,'i':0,'o':0,'u':0}

flag=False

for i in str:

    if i in vow:
        vow[i]+=1
        flag=True
if flag==False:

    print(f"There are no vowels in {str}")
else:

    for i in vow:
        if vow[i]:
            print(f"Vowel:  {i} {vow[i]}")

### OUTPUT
![image](https://github.com/user-attachments/assets/f831e1b6-dea2-4272-908b-f693714d4022)


### RESULT
Thus, python program to count the vowels of a given string was implemented successfully.

