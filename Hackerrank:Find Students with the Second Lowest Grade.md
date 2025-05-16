# 🎓 Hackerrank:Python Program to Find Students with the Highest Grade

This program reads student names and their corresponding grades, identifies the **Highest grade**, and prints the names of all students who have that grade in **alphabetical order**.

---

## 🎯 Aim

To write a Python program to:
- Read a list of students and their grades.
- Identify the largest grade.
- Print the names of students who have that grade, sorted alphabetically.

---

## 🧠 Algorithm

1. **Read** an integer `n` representing the number of students.
2. **Read** each student’s name and grade, and store them as a sublist inside a list.
3. **Extract** all the grades and sort them.
4. **Identify** the largest grade from the sorted grade list.
5. **Collect** names of all students whose grade matches the second lowest grade.
6. **Sort** the names alphabetically.
7. **Print** each name on a new line.

---

## 💻  Program

```
a=eval(input())
tot={name:sum(marks) for name,marks in a.items()}
topper=max(tot,key=tot.get)
print(tot)
print(f"Topper is:  { topper} with marks =  {tot[topper]}")
```

## Output
![image](https://github.com/user-attachments/assets/136cf626-e02b-46a0-b5c3-05969b60c05a)


## Result


