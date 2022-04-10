# Python-Basic-and-Fundamental-Part-IV

**Python OOP (Object-Oriented Programming)**
Python Object-Oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. The main concept of OOPs is to bind the data and the functions that work on that together as a single unit so that no other part of the code can access this data.

**Main Concepts:**

1. Class
A class is a collection of objects. A class contains the blueprints or the prototype from which the objects are being created. It is a logical entity that contains some attributes and methods.
2. Object
The object is an entity that has a state and behavior associated with it. Integers, strings, floating-point numbers, even arrays, and dictionaries are all objects. 
3. Method
When we call a method of this object as myobject.method(arg1, arg2), this is automatically converted by Python into MyClass.method(myobject, arg1, arg2) – this is all the special self is about.

**init function**

The init function is similar to constructors in C++ and Java. It is run as soon as an object of a class is instantiated. The functon is useful to do any initialization you want to do with your object.

**Object Method**
Objects can also contain methods. Methods in objects are functions that belong to the object.

**Class Method**

The @classmethod decorator is a built-in function decorator that is an expression that gets evaluated after your function is defined. The result of that evaluation shadows your function definition. A class method receives the class as an implicit first argument, just like an instance method receives the instance.

**Static Method**

A @staticmethod does not receive an implicit first argument.

**Pydoc**

The pydoc module automatically generates documentation from Python modules. The documentation can be presented as pages of text on the console, served to a web browser, or saved to HTML files.

**File Handling (TXT File)**

File handling is an important part of any web application.

Python has several functions for creating, reading, updating, and deleting files.

The key function for working with files in Python is the open() function.

The open() function takes two parameters; filename, and mode.

There are four different methods (modes) for opening a file:

"r" - Read - Default value. Opens a file for reading, error if the file does not exist

"a" - Append - Opens a file for appending, creates the file if it does not exist

"w" - Write - Opens a file for writing, creates the file if it does not exist

"x" - Create - Creates the specified file, returns an error if the file exists

**Unit Test**

The Python standard library includes a unittest module to help you write and run tests for your Python code. Tests written using the unittest module can help you find bugs in your program, and prevent regressions from occurring as you change code over time. unittest is useful for ensuring that all code that is created has a suitable set of tests.

**OS**

The os.mkdir() function is used to create new directory. In Python, we can create a directory using mkdir which is a method in Python provided by the OS module for interacting with operating systems. This function os.mkdir() returns nothing which means it cannot return any value

**Math module**

The math module contains a list of functions for performing mathematical calculations.

**Datetime**

Datetime is a library or module that is called if you need any related operations for the sake of time.

**Random**

We can create a series of random number by using random module. what we need to do is just simply import the module and use the function within the module in our program

**Import sys**

sys can be use as a way to define what kind of error we are facing in our program
