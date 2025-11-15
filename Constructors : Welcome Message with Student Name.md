# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

```
class student:
    def __init__(self,string):
        self.string=string
    def disp(self):
        return self.string
string=input()
obj=student(string)
print("This is non parametrized constructor")
print(f"Hello {obj.disp()}")
```

## Output

<img width="889" height="234" alt="image" src="https://github.com/user-attachments/assets/dd1ed1a6-8e4a-453c-96ff-827eff8352a0" />


## Result
Thus to write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user is created and executed successfully.
