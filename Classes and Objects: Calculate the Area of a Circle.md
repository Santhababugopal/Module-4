# Classes and Objects in Python: Calculate the Area of a Circle

##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math

class umbrella:

    def rain(self, radius):
        area = math.pi * radius ** 2
        print("Area of circle: {:.2f}".format(area))

r = float(input())

obj = umbrella()
obj.rain(r)


```

## Output
<img width="811" height="208" alt="image" src="https://github.com/user-attachments/assets/e2b47f86-84a3-4e20-9100-acbdb775507b" />

## Result
Thus, the Python program to calculate the area of a circle using a class cse and method mech was successfully executed and the area was displayed based on user input.
