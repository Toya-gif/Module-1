# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find minimum between three float numbers using conditional Expression

## ALGORITHM  
1)Start
2)Input three numbers: a, b, and c
3)Check if a is less than both b and c:
4)If True, print a as the minimum
5)Else if b is less than both a and c:
6)If True, print b as the minimum
7)Else:
8)Print c as the minimum
9)End

## PROGRAM
```python
# Reg.No-
# Name-
# Write your code here

a=float(input())
b=float(input())
c=float(input())
if a<b and a<c:
    print(f"The minimum of {a}, {b}, {c} is {a}")
elif b<a and b<c:
    print(f"The minimum of {a}, {b}, {c} is {b}")
else:
    print(f"The minimum of {a}, {b}, {c} is {c}")
```

## OUTPUT
![image](https://github.com/user-attachments/assets/7c23d9f9-e18f-4be7-85cd-ea65f9255deb)

## RESULT
Thus Python program to find minimum between three float numbers using conditional Expression is done and verified.
