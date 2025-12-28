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
data=eval(input())

sort=dict(sorted(data.items()))

print("Keys and Values sorted in alphabetical order by the key")

for key, value in sort.items():

    print(f"({key}, {value}) ",end="")

## Sample Output
![WhatsApp Image 2025-12-27 at 8 09 59 PM](https://github.com/user-attachments/assets/81b506a3-f084-40f2-baa9-c66d62eb7c57)

## Result
Thus, the program has been successfully executed.
