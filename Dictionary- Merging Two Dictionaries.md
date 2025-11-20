## Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program

```
dict1 = eval(input())
dict2 = eval(input())
dict1.update(dict2)
print(dict1)


```

## Output
<img width="1131" height="239" alt="image" src="https://github.com/user-attachments/assets/b5200644-7ddd-44f3-81ac-1c9bf579f34d" />

## Result
Thus, the Python program to merge two dictionaries using the update() method was successfully executed, and the combined dictionary was displayed.
