# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

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
```
# Start the program

# Define a dictionary with key-value pairs
dictionary = {
    "banana": 30,
    "apple": 10,
    "orange": 20,
    "grapes": 40
}

# Sort by keys
sorted_by_keys = dict(sorted(dictionary.items()))

# Sort by values
sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

# Display the original and sorted dictionaries
print("Original Dictionary:", dictionary)
print("Dictionary Sorted by Keys:", sorted_by_keys)
print("Dictionary Sorted by Values:", sorted_by_values)

# End the program
```
## Sample Output
<img width="843" height="147" alt="WhatsApp Image 2026-06-02 at 9 01 07 AM" src="https://github.com/user-attachments/assets/0eef4797-4a83-4048-ac84-a2bc8ed8eae7" />


## Result
To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order is successfully.

