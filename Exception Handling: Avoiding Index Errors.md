# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim :
To write a Python program using a class 'cse' and a function 'mech' to find the perimeter (circumference) of a circle.
## 🧠 Algorithm :
1.Define a class 'cse'.

2.Inside the class, define a method 'mech' that accepts the radius of the circle.

3.Calculate the perimeter (circumference) using the formula:

Perimeter
=
2
×
𝜋
×
   * radius
   * Perimeter=2×π×radius
4.Print the result.

The program will take the radius as input and display the calculated perimeter.
## 🧾 Program :
```.py
import math
class cse:
    def __init__(self,radius):
        self.radius=radius
    def mech(self):
        print(f"Perimeter of circle: {(math.pi*2*self.radius):.2f}")
        
radius=int(input())
cir1=cse(radius)
cir1.mech()
```

## Output :
![image](https://github.com/user-attachments/assets/adaa57d3-5328-41e7-b4e0-e99b75cac818)



## Result :
The program successfully calculates and prints the perimeter (circumference) of a circle based on the given radius.
