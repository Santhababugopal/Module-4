# File Handling in Python:  To merge two files into a third file.

##  Aim
To write a Python program that merges the contents of two files into a third file.

##  Algorithm
1.Start the program.

2.Open the first file in read mode.

3.Open the second file in read mode.

4.Open a third file in write mode.

5.Read the contents of the first file and write them into the third file.

6.Read the contents of the second file and append them to the third file.

7.Close all the files.

8.Display a success message.

9.End the program.

##  Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    with open(file1_path,'r') as f1:
        read=f1.read()
    with open(file2_path,'r') as f2:
        write =f2.read()
    with open(output_file_path,'w') as f3:
        output=f3.write(read+write)

def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

```

## Output
<img width="1144" height="486" alt="image" src="https://github.com/user-attachments/assets/5ff4a013-9990-4547-9c0b-381922ee8121" />

## Result
Thus, the Python program successfully merges the contents of two files into a third file.
