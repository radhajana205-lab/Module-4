# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values
## NAME:JANARTHANI R
## REF NO: 25017541
This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
data = {

    'banana': 'yellow',
    
    'apple': 'red',
    
    'cherry': 'dark red',
    
    'mango': 'orange'
    
}

sorted_by_keys = dict(sorted(data.items()))

sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Original Dictionary:")

print(data)

print("\nDictionary Sorted by Keys:")

print(sorted_by_keys)

print("\nDictionary Sorted by Values:")

print(sorted_by_va


## Sample Output
Original Dictionary:
{'banana': 'yellow', 'apple': 'red', 'cherry': 'dark red', 'mango': 'orange'}

Dictionary Sorted by Keys:
{'apple': 'red', 'banana': 'yellow', 'cherry': 'dark red', 'mango': 'orange'}

Dictionary Sorted by Values:
{'cherry': 'dark red', 'mango': 'orange', 'apple': 'red', 'banana': 'yellow'}

## Result
Thus, the Python program to sort a dictionary by keys and by values in alphabetical order was executed successfully and the sorted dictionaries were displayed correctly.
