# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```

# Name: Vikram GS
# Reg No: 212222060296

n = int(input("Enter limit: "))
even_list = []

for i in range(1, n+1):
    if i % 2 == 0:
        even_list.append(i)

print("Even numbers:", even_list)
```

### OUTPUT

Enter limit: 10
Even numbers: [2, 4, 6, 8, 10]

### RESULT

String slicing operations are performed successfully.
