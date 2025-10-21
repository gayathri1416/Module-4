# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
import math
class cse:
    def mech(self, radius):
       
        area = math.pi * radius * radius
        return area
radius = float(input())
circle = cse()

area = circle.mech(radius)
print(f"Area of circle: {area:.2f}")

## Output
<img width="838" height="231" alt="image" src="https://github.com/user-attachments/assets/3a25b7e1-4af8-44f5-a805-367ee9ac144d" />

## Result
Thus the Python program that calculates the area of a circle based on the radius provided by the user is executed successfully.
