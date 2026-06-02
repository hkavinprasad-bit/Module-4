## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {"a": 10, "b": 20}
dict2 = {"b": 30, "c": 40}

def merge():
    merged_dict = {**dict1, **dict2}
    print(merged_dict)

merge()
```

## Output
<img width="846" height="110" alt="WhatsApp Image 2026-06-02 at 9 00 56 AM" src="https://github.com/user-attachments/assets/f50adca5-e409-4bf7-8c22-7b3826091047" />


## Result
To write a Python program that merges **two dictionaries** and combines their key-value pairs is successfully.
