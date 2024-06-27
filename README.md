[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15228719&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
  
   - Python is a high-level, interpreted programming language that is widely used for many different purposes, from web development to scientific computing to machine learning. Key features that make python popular: Its easy to learn due to its simple syntax. It is versatile because it supports multiple programming paradigms, including procedural, object-oriented, and functional programming. It has an extensive standard library that provides modules and functions for various tasks, from web development to data analysis.
   - Use cases of python include: Web Development - Python frameworks like Django and Flask enable rapid development of robust web applications. Data Science and Analysis - Libraries such as Pandas, NumPy, and Matplotlib make Python ideal for data manipulation, analysis, and visualization. Machine Learning and AI - Python's libraries, including TensorFlow, Keras, and Scikit-learn, facilitate the development of machine learning models and AI applications.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
  
   - Steps of installing Python include: check if Python is already installed on your computer. Download python by visit the official python website at python.org. Choose the right version. Download the installer by choosing installer that matches your OS. After downloading, locate the installer file and run it. Add Python to PATH. Verify the installation by running python --version in the command prompt.
   - Verification of installation aand set up virtual environment: Open a new CMD prompt. Install virtualenv through the command pip install virtualenv. If you are not an administrator do not update if prompted. Check that virtualenv is installed through the command pip --version

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
  
   - print("Hello, World!")
   - print: A function that outputs text to the console. "Hello, World!": A string which are normally in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
     
   - Basic data types in Python: Integer holds signed integers of non-limited length. Float holds floating decimal points and it's accurate up to 15 decimal places. List which stores ordered collection of similar or different types of items and is enclosed within brackets []. Tuple stores ordered sequence of items same as a list but is immutable and is enclosed within parantheses (). String holds sequence of characters represented by either single or double quotes. Bool stores two values true or false. Dictionary holds an ordered collection of elements in key/value pairs.  Set stores an unordered collection of unique items enclosed in braces {}.
   -   age = 5                                                # int
       y = 3.14                                             # float
       name = "Jewel"                                       # str
       is_student = True                                    # bool
       languages = ["Dart", "HTML", "Python"]               #list
       location = {"country":"Kenya", "city":"Nairobi"}     #dictionary
       

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
     
   - Conditional statements are powerful constructs that are used to automate repetitive tasks and control the flow of their programs based on certain conditions.
   - if-else
   - x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")
   - for-loop
   - for i in range(5):
    print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
     
   - A function is a block of statements that return the specific task. Functions are crucial because it reduces code repitition which saves time and making the code cleaner.
   - def add(a, b):
    return a + b
result = add(3, 4)
print(result)  

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
  
   -  List stores ordered collection of similar or different types of items and is enclosed within brackets [] while dictionary holds an ordered collection of elements in key/value pairs.
   - # List
numbers = [1, 2, 3, 4, 5]
print(numbers[2])  # Outputs: 3

  # Dictionary
person = {"name": "Jewel", "age": 20}
print(person["name"])  # Outputs: Jewel


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
     
   - Exception handling allows the program to continue to execute even if an error occurs.
   - try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("This block executes no matter what")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
  
   - Module is a single file containing Python code. Package is a collection of modules that are organized in a directory hierarchy.
   - import math
print(math.sqrt(16))  # Outputs: 4.0

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
   
    - Reading files: Involves methods ( read() , readline() , readlines() ) to retrieve data from a file. Writing files: Involves methods ( write() , writelines() ) to store data into a file.
    - with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
    - lines = ["First line", "Second line"]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')



References
plp python notes
LinkedIn · Azhar Khan
How to Install Python: A Step-by-Step Guide
Shiksha
https://www.shiksha.com › ... › Programming Articles
GeeksforGeeks
https://www.geeksforgeeks.org › reading-writing-text-fi...
Reading and Writing to text files in Python - GeeksforGeeks

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


