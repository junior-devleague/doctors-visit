# doctors-visit
[Beginner] Basic intro python project going over variables, strings, integers, and functions

You are helping out at your Aunt Rita's doctors office for the summer and she needs your help creating a form for her patients to fill out so that she can help them get better!

## Objective
Use **Python** to create a program that uses functions to store patient information. Correctly use variables to store patient information as strings or intergers, ask for user input, and print out required information. 

## Prerequisites
Students need no prior knowledge of Python as this is designed for beginners.

## Concepts

Python | Description
-------|-------------
Python | Python is an interprested, object-oriented, user-friendly programming language
Variable | when one letter or word is used to represent a different letter, word, number or value
String | Any piece of data that is inbetween two '' (ex: 'My dog has flee's', 'Bob', '123 Redtree road', etc.)
Integer | A plain, whole number (ex: 50, 200, etc.)
Float | Fractional number (ex: 11.7, 2.5, etc.)
function | Blocks of code that we can build to do a specific job

### Variables
- When naming your variables, you should use lowercase letters and if you use two words they should be connected with an underscore (ex: my_name is correct, My_Name is not correct)
- There are three basics types of information we can store in variables: Integers, Strings and Floats

To store a value you can create a variable and set it equal to a value
For example:
  - string_variable_name = "Alice"
  - integer_variable_height = 66
  - float_variable_grade = 77.80
  
Now everytime your print your variable, you will get the value you stored.
For example:
  - print(string_variable_name)
  - Alice
Combining strings, integers and floats
  - So far we have only attempted to combie items that share a data type (ex: string + string, or integer + integer)
  - If we want to combine different data types we need to use Python's built in functions to define each of our data types.
  
### Functions
Now that we know what variables are, we can use them to build functions. Python functions are blocks of code that we can build to do a specific job. We build these functions once and then we can reuse them in our code just by typing their name. 
for example: If I am writing a program that is going to constantly add two numbers I can create a function to do it and then use that single line to call my function when I need to add numbers. 
  
Built in Functions:
  - int(): This is what we use to convert a string or float into an integer
  - float(): This converts a string or integer to a float
  - raw_input(): This gets information from a user and stores it in the computer to use later
  - str(): This converts an interger, float, or other information into a string
  
### Comments
In Python comments are words or sentences that the computer will not read as code. We tell the computer this by using a hashtag at the begining of what we want to be commented. See the example below for a recap on everything we have covered. 
- Usually at the beginning of your program you will write a few comment lines explaining what your program does, who wrote it, the date, etc.
- You can and should also use comments throughout your program. Before functions to explain what the function does, or what a specific line of code does.

Example Code: 
  
  ``` Python
# This is a python program that asks for the users name

  def example():
    user_name = input('What is your name? ')
    # Creates a variable user_age and defines the value as a float 
    user_age = float(16.5)
    print('Its very nice to meet you ' + user_name)
    print(user_age) # Print's the users age
 ```

Here we used a hashtag/number sign to write a comment about what our program does. Then we created a function named example. Then we created a variable called user_name and asked the user for input of what their name is. Then we created another variable called user_age and set it equal to 22.5 and defined that it is a float. Which means that it will print out the exact value. If we had defined it as an int(), it would have rounded the number up to 23. Then we did two seperate print statements, the first we put a string in and then added our variable to it. The second print statment just prints the output. 


## Your Challenge
1. Create a new python document titled doctors-visit.py
2. 


Stretch Goal
Summary
This is a beggining Python project students should do as one of the first few python projects



