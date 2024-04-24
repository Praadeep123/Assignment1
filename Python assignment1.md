1.	Write a Python program to print "Hello Python"?

def hii():
    return"hello python"
hii()    

'hello python'

2.	Write a Python program to do arithmetical operations addition and division.?

def addition(a,b):
    return(a+b)
addition(3,4)    

def division(a,b):
    return(a/b)
division(4,2)    

3.	Write a Python program to find the area of a triangle?

def area_of_triangle(base,height):
    area=0.5*base*height
    return area
base_length=float(input("enter the length of the base of the triangle:"))
height_length=float(input("enter the length of the height of the triangle:"))                  
area_of_triangle(base_length,height_length)  


enter the length of the base of the triangle: 10
enter the length of the height of the triangle: 20
100.0

4.	Write a Python program to swap two variables?

def swap_variable(a,b):
    a,b = b,a
    return a,b
a=10
b=20
swap_variable(a,b)


(20, 10)

5.	Write a Python program to generate a random number?

import random
random.randint(0,9999)


3954



```python

```
