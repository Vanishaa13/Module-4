## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
a=eval(input())

b=eval(input())

c=a.copy()

c.update(b)

print(c)

## Output
![WhatsApp Image 2025-12-27 at 8 09 06 PM](https://github.com/user-attachments/assets/17acbb8e-202c-4379-a53b-6476c58cadef)

## Result
Thus the program executed successfully.
