# Doctors-visit
[Beginner] Basic intro python project going over variables, strings, integers, and functions

You are helping out at your Aunt Rita's doctor's office for the summer and she's having a hard time keeping track of patients' symptoms. Help her by creating a form for her patients to fill out so that she can help them get better!

## Objective
Use **Python** to create a program that uses functions to store patient information. Correctly use variables to store patient information as strings or integers, ask for user input, and print out required information. 

## Prerequisites
Students need no prior knowledge of Python as this lesson is designed for beginners.

## Concepts

Python | Description
-------|-------------
Python | Python is an interpreted, object-oriented, and user-friendly programming language.
Variable | A letter or word used to represent a different letter, word, number, or value, as with algebra.
String | Any piece of data that is between two '' or "". (ex: 'My dog has fleas', "Bob", '123 Redtree road', "etc.")
Integer | A plain, whole number, the same as you'd see in math class. (ex: 50, 200, etc.)
Float | A fractional number. (ex: 11.7, 2.5, 7.0, etc.)
function | Blocks of code that we can build to do a specific job, and call on at a different time

### Variables
- When naming your variables, you should use lowercase letters and if you use two words they should be connected with an underscore (ex: my_name is correct, My_Name is not correct) -- this is known as snake casing. There are other acceptable formats for naming, but this is the convention for python.
- There are three basics types of information we can store in variables: Integers, Strings and Floats

To store some information, you can create a variable and set it equal to the information you want to store.
For example:
  - string_variable_name = "Alice"
  - integer_variable_height = 66
  - float_variable_grade = 77.80
  
We can also combine variables of the same type using a + symbol!
For strings, it works like this:
- hello = "Hi"
- name = "Alice"
- greeting = hello + " " + name

greeting is now equal to "Hi Alice"
For numbers, it works the same way as addition does in real life. In addition, you can do all the rest of your basic math using +, -, \*, and / to do addition, subtraction, multiplication, and division.

Now you can use the print function to print out the value stored in your variable.
For example:
  - print(string_variable_name)
  - Alice
  
Combining strings, integers and floats:
  - So far we have only attempted to combine items that share a data type (ex: string + string, or integer + integer)
  - If we want to combine different data types we need to use Python's built in functions to define each of our data types.
  
### Functions
Now that we know what variables are, we can use them to build functions. Python functions are blocks of code that we can build to do a specific job. We build these functions once and then we can reuse them in our code just by typing their name. 
for example: If I am writing a program that is going to constantly add two numbers I can create a function to do it and then use that single line to call my function when I need to add numbers. 
  
Built in Functions:
  - int(): This is what we use to convert a string or float to an integer
  - float(): This converts a string or integer to a float
  - input(): This gets information from a user and stores it in the computer to use later
  - str(): This converts an integer, float, or other information to a string
  
Now that we know these, we can try to combining a string with an integer, or creating a function to add 2 numbers.
To add a string, and an integer, we do this:
- integer = 5
- string = " is a number"

if we try combining the two right now, we'll get an error saying "unsupported operand type(s) for +: 'int' and 'str'". Confusing, right? However, that error's just saying that you can't combine an integer and a string. If we do:
- integer = 5
- string_of_integer = str(integer)
- string = " is a number"

we can combine string_of_integer and string successfully.

To create a function to add numbers, we need to define it, and put some code that will run in it, like this:
```
def add(num1, num2):
  output = num1 + num2
```

as you can see, to define a function you do 'def function_name(args):'. you can create a function with any number of arguments you could need, from 0 to 255. If you have 0 arguments, you just call function_name(), and with multiple arguments you need to separate each argument with commas. At the moment, we've created a function in the above example but aren't doing anything with it. The function will only run when you *call* it, by typing function_name(arguments). For example, with:
```
def add(num1, num2):
  output = num1 + num2
  return output
sum = add(3, 5)
print(sum)
````
the function only runs when you run add(3, 5), and not when you're defining the function.

We can also set a variable equal to a user's input by saying 'variable_name = input("prompt for user")'. This will show the user the prompt that you give them in input, and will then set the variable equal to whatever they input in response to the prompt.

### Comments
In Python comments are words or sentences that the computer will not read as code. We tell the computer that a comment is a comment by using a hashtag at the begining of what we want to be commented. See the example below for a recap on everything we have covered. 
- Usually at the beginning of your program you will write a few comment lines explaining what your program does, who wrote it, the date, etc.
- You can and should also use comments throughout your program. Use them before functions to explain what the function does, or next to a line of code to explain what it does.

Example Code: 
  
  ``` Python
# This is a python program that asks for the users name

  def example():
    user_name = input('What is your name? ')
    # Creates a variable user_age and defines the value as a float 
    user_age = float(16.5)
    print('Its very nice to meet you ' + user_name)
    print(user_age) # Prints the user's age
 ```

Here we used a hashtag/number sign to write a comment about what our program does. Then we created a function named example. Then we created a variable called user_name and asked the user for input of what their name is. Then we created another variable called user_age and set it equal to 16.5 and defined that it is a float. Which means that it will print out the exact value. If we had defined it as an int(), it would have rounded the number up to 23 (note: you *do not* need to use a float statement there, as it's implicitly defined as a float. The float is there for example's sake). Then we did two seperate print statements -- in the first we combine a string and our user_name variable and then print that, and in the second we just print the user's age, stored as user_age. 


## Your Challenge
1. Create a new python document titled doctors-visit.py
2. At the top, write a comment that describes what the program does, your name, and the date
3. Create a function called basic_info
4. Create a variable called name and set it equal to an input asking the user for their age
5. Create a variable called age and set it equal to an input asking the user for their age
6. Create a variable called home_address and set it equal to an input asking the user for their address
7. Create a variable called reason_for_visit and set it equal to "I am sick"



Stretch Goal



