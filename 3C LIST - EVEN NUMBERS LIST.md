# Exp.No:3c
## LIST - EVEN NUMBERS LIST

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

### PROGRAM

```
def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/ed7c4457-ae3f-44e7-9595-582c59638b5a)

### RESULT
Thus the program that creates a list of even numbers from 12 to n and prints the list and its sum has been implemented and executed successfully.
