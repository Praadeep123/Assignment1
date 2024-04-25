Write a Python program to convert kilometers to miles?

def kilo_to_miles(km):
    miles=km*0.621371
    return miles
kilometers=float(input("enter distance in kilometers:"))
kilo_to_miles(kilometers)

enter distance in kilometers: 10
6.21371

2. Write a Python program to convert Celsius to Fahrenheit?

def celsius_to_fahrenheit(celsius):
    fahrenheit=celsius*9/5+32
    return fahrenheit
celsius=float(input("enter temperature in celsius:"))
celsius_to_fahrenheit(celsius)  

enter temperature in celsius: 15
59.0

3. Write a Python program to display calendar?
import calendar
year=int(input("enter the year:"))
month=int(input("enter the month(1-12):"))
print(calendar.month(year,month))

enter the year: 2024
enter the month(1-12): 5
      May 2024
Mo Tu We Th Fr Sa Su
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31

4. Write a Python program to solve quadratic equation?


```python

```

5. Write a Python program to swap two variables without temp variable?

a=3
b=10
print("before swapping:")
print("a=",a)
print("b=",b)
a,b=b,a
print("\nAfter swapping:")
print("a=",a)
print("b=",b)

before swapping:
a= 3
b= 10

After swapping:
a= 10
b= 3
