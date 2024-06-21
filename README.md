[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15299282&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Answers:

   Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991
   
   Python has gained immense popularity among developers due to several key features:
   * Simplicity and Readability - Python emphasizes code readability and simplicity, making it easy to learn and use. Its syntax allows developers to write clear and concise code, enhancing productivity and reducing the time required for development and debugging.
   *Versatility - Python is a versatile language that can be used for a wide range of applications, from web development to scientific computing, data analysis, artificial intelligence (AI), machine learning, automation, and more. Its extensive standard library and third-party packages contribute to its versatility.
   *Cross-platform Compatibility - Python runs on various platforms such as Windows, macOS, Linux, and Unix, making it highly portable. This enables developers to write code once and deploy it across different systems without significant modifications.
   
   E.g 
   - Web development - Python is widely used for server-side web development. Frameworks like Django and Flask facilitate building robust and scalable web applications. For example, Instagram, a popular social media platform, was originally built using Python and Django.
   - Data Science and Machine Learning - Python is the language of choice for data scientists due to its powerful libraries such as NumPy, Pandas, Matplotlib, and scikit-learn. These libraries provide tools for data manipulation, analysis, visualization, and machine learning model development. 


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Answers:
   
   1. Visit the link https://www.python.org/downloads/ to download the    latest release of Python.
   2. Select the Python's version to download
   3. Click on the Install Now button
   Double-click the executable file, which is downloaded;
   Select Customize installation and proceed.
   Click on the Add Path check box, it will set the Python path automatically.
   4. Installation in process
   5. When installation is done, try to run python on the command prompt. Type the command python -version in case of python3.


- To verify the installation of Python, you can open a command prompt or  terminal and type ‘python --version’ or ‘python3 --version’. This command will display the installed Python version, confirming that Python is correctly installed on your system. Additionally, to set up a virtual environment for Python projects, you can use the ‘venv’ module, which is included in Python 3 by default. Navigate to your project directory in the command prompt or terminal and run ‘python -m venv env’ to create a new virtual environment named 'env' (you can replace 'env' with any name you prefer). Activate the virtual environment by running ‘source .\env\Scripts\activate’ on Windows. You will see the environment name (e.g., (env)) displayed in the command prompt or terminal, indicating that you are now working within the virtual environment.


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Answers:

   # Simple Python program to print "Hello, World!" in a hello_world.py file
   print(“Hello, World!”)
   * Comments - Comments in python start with a ‘#’’  hashtag symbol and are used to annotate code. They are ignored by the interpreter and are helpful for explaining code or making note 
   * Print Statement - The ‘print()’ function in Python is used to output text or variables to the console. In the example, print("Hello, World!") prints the string "Hello, World!" to the console.
   * Strings - In Python, strings are sequences of characters enclosed in single quotes (') or double quotes (")
   * Whitespace -  Python uses indentation to define blocks of code. Although not explicitly shown in this simple example, proper indentation (typically four spaces per level) is essential for readability and correct program execution in Python.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Answers:

   - Integer - Represents whole numbers without decimal points, such as 5 or -10.
   - Float - Represents numbers with decimal points, like 3.14 or -2.5, allowing for fractional values.
   - String - Represents sequences of characters enclosed in single (‘’) or double (“ “) quotes
   - Boolean -  Represents truth values, either True or False, used for logical operations and conditions.
   
   DEMONSTRATION
   
   # Define variables
   my_integer = 42

   my_float = 3.14

   my_string = "Hello, Python!"

   my_boolean = True
   
   # Print the variables and their types
   
   print("Integer:", my_integer, "| Type:", type(my_integer)) 

   print("Float:", my_float, "| Type:", type(my_float))

   print("String:", my_string, "| Type:", type(my_string))

   print("Boolean:", my_boolean, "| Type:", type(my_boolean))
   
   # Output
   
   Integer: 10 | Type: <class 'int'> 

   Float: 3.14 | Type: <class 'float'>

   String: Hello, Python! | Type: <class 'str'> 

   Boolean: True | Type: <class 'bool'>


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Answers:
   
   - Conditional statements in Python, such as ‘if’, ‘elif’, and ‘else’, are used to execute different blocks of code based on whether a condition is True or False. 
   - Loops in Python, such as ‘for’ and ‘while’, are used to execute a block of code repeatedly as long as a condition is met. They simplify repetitive tasks by automating the execution of code blocks multiple times.
   
   If-else statement

   age = 18 

   if age >= 18:

     print("You are an adult.") 

     else: 

     print("You are a minor.")

     
     For Loop

     for fruits in range(3): 

     print("fruits:", fruits)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Answers:

   - Python functions are a block of statements that return the specific task.
   - Python functions are useful to separate reusable code from the core app so you do not repeat yourself.
   - Python functions provide clarity.
   
   def sum_two_numbers(a, b):

          return a + b 

          result = sum_two_numbers(3, 5)

          print("sum:", result)

               Sum = 8
               
   - Function definition - Defines a sum_two_numbers function that accepts two parameters  ‘a’ and ‘b’.
   - Function body - returns the sum of ‘a’ + ‘b’ when the function is called.
   - Calling the function - ‘result = sum_two_numbers(3, 5) calls the sum_two_numbers function with numbers 3 and 5.
   - Output - print(“sum:”, result) prints results of the function call, which is 8.


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Answers:

   - A list is an ordered collection of items, whereas a dictionary is an unordered data collection in a key: value pair.
   
   numbers = [1, 2, 3, 4, 5] 

     print("List:", numbers)

     numbers.append(6) 

    print("After append:", numbers)

    
    person = {"name": "Alice", "age": 30}

      print("Dictionary:", person)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Answers:

   - Exception handling in Python is a process of resolving errors that occur in a program.
   
   E.g. 
   
   def divide_numbers(a,  b):

   try:

     result = a / b

     print(“resultt:”, result)

   except ZeroDivisionError:

     print(“Error: Division by zero is not allowed.”)

   finally:

     print(“Execution complete.”)
      
      def  divide_numbers(5, 0)


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Answers:

   - Module - A file containing a set of functions you want to include in your application.
   - In python, modules are individual files containing Python code (such as functions, classes, or variables) that can be imported and used in other Python programs to promote code reuse and organization. 
   - In python, a package is a container for storing multiple python modules and are organized in a dictionary hierarchy.
   - To import a module into a python script you need to use the import keyword along with the desired module name.
   
   E.g 
   
   Import math

   number = 16 

   sqrt_value = math.sqrt(number) 

   print("Square root of", number, "is", sqrt_value)

   Square root of 16 is 4


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Answers:

    The key function for working with files in python is the open() function. The open() function takes two parameters; filename and mode  * Reading files: involves methods ( read(), readline(), readlines() ) to retrieve data from a file.
    * Writing files: involves methods ( write(), writelines() ) to store data into a file.

    # read_hello.txt

    read_file('C:\Users\Palesa\Documents\hello.txt')

    def hello(file_path):

    try:

        with open(file_path, 'r') as hellofile:

            content = hello.read()

            print(content)

    except FileNotFoundError:

        print(f"The file {file_path} does not exist.")
    except IOError:

        print(f"An error occurred while reading the file {file_path}.")

      # write_to_hello.txt

      def write_to_hello(file_path, lines):
    try:
        with open(file_path, 'w') as hellofile:
            for line in lines:

                hello.write(f"{line}\n")
    except IOError:

        print(f"An error occurred while writing to the file {file_path}.")
        
        Sources/References 
        - Power Learn Project Day 2- Environment set-up,Lesson: How to set up python environment
        - geeksforgeeks.org
        - datacamp.org
        - almabetter.com
        - w3schools.com



    


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


