# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.


### PROGRAM
s=eval(input())

t=()

p=0

i=0

sum=0

while p<s-5:

    i=i+1
    p=i*5
    t=t+(p,)
    
print(t,end="")


### OUTPUT
![image](https://github.com/user-attachments/assets/da06de57-457c-498f-a3af-0100b4d66831)


### RESULT
Thus, Python program to create a tuple containing all multiples of 5 up to a given number **N** was implemented successfully.

