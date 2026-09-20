# Exception Handling in Python: Avoiding Index Errors
## NAME: JANARTHANI R
## REF NO: 25017541
## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
list1 = [10, 20, 30, 40]

try:

    print(list1[5])   # Accessing out-of-range index
    
except IndexError:

    print("You're out of list range")


## Output
You're out of list range

## Result
Thus, the Python program to handle an IndexError using try-except block was executed successfully, and a custom error message was displayed when an out-of-range index was accessed.
