# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output

<img width="314" height="40" alt="image" src="https://github.com/user-attachments/assets/0f61a575-d5c2-4d2c-9fbc-f55f78811bb8" />


## Result
Thus, the Python program to handle an IndexError while accessing an element beyond the available range of a list was executed successfully and the output was verified.
