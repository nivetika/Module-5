# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 

```
class add:
    def addition(self,a,b):
        print(a+b)
class Multiply:
    def multi(self,a,b):
        print(a*b)
class Division(add,Multiply):
    def divi(self,a,b):
        print(a/b)
x=int(input())
y=int(input())
obj=Division()
obj.addition(x,y)
obj.multi(x,y)
obj.divi(x,y)
```
## Output Example

<img width="320" height="193" alt="image" src="https://github.com/user-attachments/assets/a8063aa0-5fc7-4bc6-ac76-a41994c7d725" />

## Result
Thus to demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes is created and executed successfully.
