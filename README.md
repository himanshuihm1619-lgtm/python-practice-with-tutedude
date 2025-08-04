# python-practice-with-tutedude

# Assignment 1: Basic Python Concepts  

This assignment covers **Module 2: Basic Python Concepts** and includes two tasks:  

---

## 📌 Task 1: Perform Basic Mathematical Operations  

### Description:  
The program takes two numbers as input from the user and performs:  
- Addition  
- Subtraction  
- Multiplication  
- Division  

### Code Snippet:  
```python
x = input("Enter the first number:  ")
y = input("Enter the second number: ")
x = float(x)
y = float(y)

add = x + y
sub = x - y
multi = x * y
div = y / x

print("Addition: ", add)
print("Subtraction: ", sub)
print("Multiplication: ", multi)
print("Division: ", div)

Example Run:
Enter the first number:  10
Enter the second number: 5

Addition:  15.0  
Subtraction:  5.0  
Multiplication:  50.0  
Division:  0.5

📌** Task 2: Create a Personalized Greeting
Description:
The program takes the user's first name and last name as input and prints a personalized greeting.**

Code Snippet:

a = input("Enter your first name: ")
a = str(a)
b = input("Enter your last name: ")
b = str(b)

Full_name = a + b

print("Hello,", Full_name + "! Welcome to python program.")

Example Run:
Enter your first name: Himanshu  
Enter your last name: Bhardwaj  

Hello, HimanshuBhardwaj! Welcome to python program.

