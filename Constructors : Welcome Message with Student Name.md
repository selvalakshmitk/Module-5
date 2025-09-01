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
class Student:

def __init__(self,x):

    self.x=x
    
    print("This is non parametrized constructor")
    
def show(self,x):  

    print("Hello",x)  
x=input()

student = Student(x)

student.show(x)

## Output
![WhatsApp Image 2025-09-01 at 19 07 02_549c1970](https://github.com/user-attachments/assets/00276d71-360a-4774-b967-9bf51547b89f)


## Result
Thus, Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user is excuted and verified.
