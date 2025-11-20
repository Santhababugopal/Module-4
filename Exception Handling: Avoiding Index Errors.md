# Exception Handling in Python: Avoiding Index Errors

##  Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

##  Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

##  Program
```
try:
    a=int(input())
    b=int(input())
    print(a+b)
except Exception:
    print("cannot add integer with string")
    

```
## Output
<img width="927" height="309" alt="image" src="https://github.com/user-attachments/assets/75b5bd4c-dd36-45b6-9c00-d48653de24ec" />

## Result
Thus, the Python program successfully demonstrates IndexError handling using a try–except block, preventing the program from crashing when an invalid list index is accessed.
