#  Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

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

## Program
```
dic={1:2,5:12,6:18,4:24,2:56,3:323}
sor=sorted(dic.items(),key=lambda item: item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sor)
```

## Sample Output
<img width="1128" height="174" alt="image" src="https://github.com/user-attachments/assets/8e5ad2c6-ce4c-4941-adf4-912e76f0a67d" />

## Result
Thus, the Python program to sort a dictionary by both keys and values was successfully written and executed.
