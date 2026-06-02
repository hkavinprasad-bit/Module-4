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
list1 = [10, 20, 30]

try:
    result = list1[5]  # Out of range index
    print(result)
except IndexError:
    print("You're out of list range")
```

## Output
<img width="622" height="159" alt="WhatsApp Image 2026-06-02 at 9 01 17 AM" src="https://github.com/user-attachments/assets/afb72750-56bf-4b6b-9ed3-c43acebab1a9" />


## Result
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is successfully.
