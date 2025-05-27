# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 9

### AIM  
To create a tuple of multiples of 9 up to N and print the tuple and its length.

### ALGORITHM

1. Start the program.
2. Accept input from the user for the value of N.
3. Initialize an empty list a.
4. Loop from 1 to N - 1:
  For each number i, check if it is divisible by 9 using i % 9 == 0.
  If true, append i to the list a.
5. Convert the list a into a tuple b.
6. Print the tuple b.
7. Print the length of the tuple using len(b).
8. End the program.

### PROGRAM

```
n=eval(input())
a=[]
for i in range(1,n):
    if i%9==0:
        a.append(i)
b=tuple(a)
print(b)
print("Length of the tuple is",len(a))

```

### OUTPUT
![image](https://github.com/user-attachments/assets/8af2f190-019a-4d42-93b2-177d7b642ca3)

### RESULT

Thus the program to create a tuple of multiples of 9 up to N and print the tuple and its length has been implemented and executed successfully.
