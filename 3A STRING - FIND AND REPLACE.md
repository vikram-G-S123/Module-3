# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
# Name: Vikram GS
# Reg No: 212222060296

string = input("Enter a string: ")
old = input("Enter word to find: ")
new = input("Enter replacement word: ")

updated_string = string.replace(old, new)

print("Updated String:", updated_string)
```

### OUTPUT

Enter a string: hello world
Enter word to find: world
Enter replacement word: python
Updated String: hello python

### RESULT

Thus, all the programs were executed successfully and verified.
