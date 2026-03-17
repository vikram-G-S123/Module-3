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

---

### PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

n = int(input("Enter limit: "))
result = tuple(i for i in range(1, n+1) if i % 5 == 0)

print("Tuple:", result)

```

### OUTPUT

Enter limit: 20
Tuple: (5, 10, 15, 20)

### RESULT

String slicing operations are performed successfully.
