# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program

```
class Details:
    def __init__(self,id,name,gender):
        self.id=id
        self.name=name
        self.gender=gender
class Employee(Details):
    def __init__(self,id,name,gender,company,dept):
        Details.__init__(self,id,name,gender)
        self.company=company
        self.dept=dept
    def display(self):
        print("Employee Object")
        print("Id: ",self.id)
        print("Name: ",self.name)
        print("Gender: ",self.gender)
        print("Company: ",self.company)
        print("Department: ",self.dept)
class Patient(Details):
    def __init__(self,id,name,gender,hospital,dept):
        Details.__init__(self,id,name,gender)
        self.hospital=hospital
        self.dept=dept
    def display(self):
        print("\nPatient Object")
        print("Id: ",self.id)
        print("Name: ",self.name)
        print("Gender: ",self.gender)
        print("Hospital: ",self.hospital)
        print("Department: ",self.dept)
id=int(input())
name=input()
gen=input()
com=input()
dept=input()

did=int(input())
dname=input()
dgen=input()
dhos=input()
ddept=input()

a=Employee(id,name,gen,com,dept)
b=Patient(did,dname,dgen,dhos,ddept)
a.display()
b.display()
```
## Sample Output

<img width="748" height="441" alt="image" src="https://github.com/user-attachments/assets/df549ba4-d772-4417-8d43-ee2d518ba9d2" />

## Result
Thus to write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details is created and executed successfully.

