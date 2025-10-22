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
```
import math
class cse:
    def _init_(self, r):
        self.area = math.pi * (r ** 2) 
    def mech(self):
        print("Area of circle:", round(self.area, 2))
r = float(input())
res = cse(r)  
res.mech()
```

## Output
<img width="516" height="175" alt="image" src="https://github.com/user-attachments/assets/4ce276da-f841-4708-b8b1-8a7faddb63b9" />


## Result
The Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation is executed successfully.
