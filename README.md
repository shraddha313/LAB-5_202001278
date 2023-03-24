# LAB-5_202001278

# LAB-5
# IT 314 Software Engineering
# 
# Name: Doshi shraddha vimalbhai
# Student ID: 202001278
# Static Code Analysis of a git repository using mypy tool </br>
Reference Git Repository:https://github.com/SharwariSM/Hostel-management-system </br>

Reference Git Repository:https://github.com/shraddha313/hiiii/tree/main/Lab-5_202001149</br>

# mypy tool:
mypy is an open-source static type checker for Python. </br>

It supports type annotations for function arguments, return values, and variables.</br>

It can also check for common type-related errors such as type mismatches, invalid method calls, and incorrect argument types.</br>

mypy supports various types of annotations including built-in types like str, int, float, etc., user-defined classes, generic types, and union types</br>.

It also provides options to customize the checking process, ignore certain files, and suppress specific error messages</br>

Type checkers help ensure that you’re using variables and functions in your code correctly. With mypy, add type hints (PEP 484) to your Python programs, and mypy will warn you when you use those types incorrectly.</br>

Python is a dynamic language, so usually you’ll only see errors in your code when you attempt to run it. Mypy is a static checker, so it finds bugs in your programs without even running them!</br>

# Process:
open vscode</br>
install mypy using command: python -m pip install mypy</br>
clone the git repository</br>
![image](https://user-images.githubusercontent.com/77456124/227498566-e72f3c81-7403-48fd-91c7-c4e4f81c8d9a.png)

then run the file </br>
using python -m mypy file name 

# 1) first repo 

![image](https://user-images.githubusercontent.com/77456124/227499331-99fab70c-fa90-45b7-94d6-11c64cd027cb.png)

first file main.py : no error 
![image](https://user-images.githubusercontent.com/77456124/227494544-75d7db00-4dc7-493c-a8bf-f188be47a741.png)
second file : hostel.py  : imcomatible import error 

# 2) second repo 

# first file hi.py 
![image](https://user-images.githubusercontent.com/77456124/227495052-5e6db3b5-89bd-492d-bc9b-b6099a58c53b.png)
error: missing stub error 

# second file .hii2.py
![image](https://user-images.githubusercontent.com/77456124/227495405-f7c16091-9bc0-4d23-8ab0-22371b6563c6.png)
error: missing stub error 

# third file : test.py 
![image](https://user-images.githubusercontent.com/77456124/227495602-9c7b663c-d4c7-4eb7-9e5e-cd2ac6a70f34.png)
error : name error
module error 
import error 

# fourth file : sh.py
![image](https://user-images.githubusercontent.com/77456124/227499094-c0f1f460-65fe-42a1-aa15-4046da6f2fbb.png)

error : installed error ,stub error 

that is how i found error in above file in repo 
