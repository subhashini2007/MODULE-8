# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Check** if the last character is a digit using the `.isdigit()` method.
4. **If true**, print that Found a match.
5. **Else**, print that not matched!.
6. **End the program.**

---

## 💻  Program
```
import re
a=input()
b='[A-Z]+[0-9]'
if re.search(b,a):
    print("Found a match!")
else:
    print("Not matched!")

```

## Output
![image](https://github.com/user-attachments/assets/54da6d07-661e-4b4c-94cc-2f0c3f0605f6)


## Result
