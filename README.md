Python Basics Assignment Question
1. What is Python, and why is it popular ?

Ans- Python is a high level open source interpreted free ware function object oriented and procedural programming language.

it is so popular beacuse -

It is beginners friendly *it is cross platform and platform independent *It is interpreted programming language *It has large community(million of developers worldwide) *It has a vast numbers of libraries and frameworks *It is used in various fields like web development, AI, Data science, automation, and more


2. What is an interpreter in Python ?

Ans- Python is a interpreted language this means python code is executed line by line by the python interpreter and it doesn't need to be compiled before running.This helps in faster testing and debugging.

3. What are pre-defined keywords in Python ?

Ans- Predefined keywords in Python are reserved words that hold special meaning and functionality within the language. These keywords are fundamental to Python's syntax and structure, and they cannot be used as identifiers (such as variable names, function names, or class names) by the programmer.

All the keywords in Python are written in lowercase except True and False.
Example - ( Boolean values - True and False , Conditional Statement - if, elif, else, etc)


4. Can keywords be used as variable names ?

Ans- No, keywords cannot be used as variable names. Keywords are reserved words in a programming language that have predefined meanings and are used to define the language's syntax and structure. Using them as variable names would lead to syntax errors because the compiler or interpreter would interpret them as language keywords rather than variable names.

5. What is mutability in Python ?

Ans- In Python, mutability refers to the ability of an object to be modified after it has been created.

Mutable Objects: These are objects whose state or content can be changed after they are initialized. When you modify a mutable object, you are altering the existing object in memory rather than creating a new one.

Examples of mutable data types in Python include:

Lists: You can add, remove, or change elements within a list.

Dictionaries: You can add, remove, or modify key-value pairs in a dictionary.

Sets: You can add or remove elements from a set.

Immutable Objects: These are objects whose state or content cannot be changed once they are created. Any operation that appears to modify an immutable object actually creates a new object with the desired changes.

Examples of immutable data types in Python include:

Numbers (integers, floats, complex numbers): You cannot change the value of an existing number object.

Strings: You cannot modify individual characters within a string; operations

like concatenation create new strings.

Tuples: Once created, the elements of a tuple cannot be changed.

6. Why are lists mutable, but tuples are immutable ?

Ans- lists are mutable because you can change the order of items in a list or reassign an item in a list. When the bracket operator appears on the left side of an assignment, it identifies the element of the list that will be assigned.

Tuples are immutable in Python because their contents once created cannot be changed. This immutability is a fundamental characteristic of tuples and is enforced by the language's design.

7. What is the difference between “==” and “is” operators in Python ?

Ans- "==" Operater :-

The ‘==’ is known as the equality operator
When the variables on either side have the exact same value, the == operator evaluation is true. Otherwise, it will evaluate as False.
"is" Operater :-

The ‘is’ is known as the identity operator
The is operator checks if two variables point to the same object in memory. It returns True if both variables are referring to the exact same object. If they point to different objects, even if the values are the same, it returns False.

8. What are logical operators in Python ?

Ans- Logical operators in Python are used to combine conditional statements and evaluate expressions based on their truth values (True or False).

logical operaters :-

"and" It returns True if both the operands are true and return false is any of one are false statement.
"or" It returns True if either of the operands is true and return false both are false statement.
"not" It change the statement condition, It returns True if the operand is false and return False if the operand is True.
9. What is type casting in Python ?
Ans- Type casting in Python, also known as explicit type conversion, is the process of manually converting a value from one data type to another using built-in functions. This is done when the programmer needs a specific data type for a variable to perform certain operations.

Example :-

int(): Converts a value to an integer
float(): Converts a value to a floating-point number
str(): Converts a value to a string
list(), tuple(), set(), dict(): Used for converting between sequence and collection types

10. What is the difference between implicit and explicit type casting ?

Ans- implicit type casting :-

Implicit casting, also called automatic type conversion, is done automatically by the compiler when different data types are mixed in an expression.
Explicit type casting :-

Explicit casting, or type casting, is performed manually by the programmer by explicitly specifying the desired data type.

11. What is the purpose of conditional statements in Python ?

Ans- Purpose of conditional statement in python :-

Decision Makin : Conditional statements (like if, elif, and else) evaluate conditions and direct the program to take different paths based on the evaluation result.
Controlling Program Flow : They allow for selective execution of code, ensuring that certain operations only occur when predefined criteria are met.
Creating Dynamic Programs : By responding to conditions, programs can adapt their behavior, handle different scenarios, and provide tailored outputs or actions.
Handling User Input and External Factors : Conditional statements are crucial for processing user inputs, responding to external data, or reacting to changes in the program's environment.

12. How does the elif statement work ?

Ans- The “elif” keyword in Python, stands for “else if”. It can be used in conditional statements to check for multiple conditions. For example, if the first condition is false, it moves on to the next “elif” statement to check if that condition is true.

13. What is the difference between for and while loops ?

Ans- For Loops:

Structure: for loops are designed to iterate over a sequence (like a list, tuple, or range) or a collection of items.
Iterations: The number of iterations is usually predetermined or easily calculable based on the sequence being iterated over
While Loops:

Structure: while loops execute a block of code repeatedly as long as a specified condition remains true.
Iterations: The number of iterations is not fixed and depends on whether the condition remains true. A while loop can execute zero or more times

14. Describe a scenario where a while loop is more suitable than a for loop.

Ans- for loops are ideal when you know the number of times you need to loop. while loops are better when the number of iterations depends on a condition that can change during execution

A for loop is usually better when you want a piece of code to run a certain number of times, and a while loop is better when the condition for the code to keep running is more general, such as having a boolean flag that is only set to true when a certain condition is met in the code block.
Practical Questions
1. Write a Python program to print "Hello, World!"

print("Hello, World!")
     
Hello, World!
2. Write a Python program that displays your name and age.

name = "Roshan Singh"
age = 21
print(f"my name is {name}")
print(f"i am {age} years old")
     
my name is Roshan Singh
i am 21 years old
3. Write code to print all the pre-defined keywords in Python using the keyword library.

import keyword
print("pre-defined keywords in python:-")
print(keyword.kwlist)
     
pre-defined keywords in python:-
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
4. Write a program that checks if a given word is a Python keyword.

import keyword

word = input("Enter the keyword: ")

if keyword.iskeyword(word):
    print(f"'{word}' is a Python keyword.")
else:
    print(f"'{word}' is not a Python keyword.")
     
Enter the keyword: True
'True' is a Python keyword.
5. Create a list and tuple in Python, and demonstrate how attempting to change an element works differently for each.

list1 = [20, 10, "Ram", 35]
tuple1 = (15, "shiva", 26)

#attempting to change an element in a list

print(f"Original List is : {list1}")

list1[2] = 15
print(f"updated list is : {list1}")

#attempting to change an element in a tuple

print(f"Original Tuple is : {tuple1}")

try:
  tuple1[2] = 16
except TypeError as e:
  print(f"Error attempting to modify tuple is: {e}")
     
Original List is : [20, 10, 'Ram', 35]
updated list is : [20, 10, 15, 35]
Original Tuple is : (15, 'shiva', 26)
Error attempting to modify tuple is: 'tuple' object does not support item assignment
6. Write a function to demonstrate the behavior of mutable and immutable arguments.

def demonstrate_mutability(num1, list1):
    print("Before modification:")
    print(f"  num1 = {num1}, id: {id(num1)}")
    print(f"  list1 = {list1}, id: {id(list1)}")

    # Attempting to modify the arguments
    num1 += 10
    list1.append(10)

    print("After modification:")
    print(f"  num1 = {num1}, id: {id(num1)}")
    print(f"  list1 = {list1}, id: {id(list1)}")

# Immutable integer
x = 5

# Mutable list
y = [1, 2, 3]

demonstrate_mutability(x, y)

print("Outside the function:")
print(f"  x = {x}, id: {id(x)}")       # Still 5, unchanged (immutable)
print(f"  y = {y}, id: {id(y)}")       # Modified to include 10 (mutable)
     
Before modification:
  num1 = 5, id: 10757864
  list1 = [1, 2, 3], id: 132074477555840
After modification:
  num1 = 15, id: 10758184
  list1 = [1, 2, 3, 10], id: 132074477555840
Outside the function:
  x = 5, id: 10757864
  y = [1, 2, 3, 10], id: 132074477555840
7. Write a program that performs basic arithmetic operations on two user-input numbers.

a = int(input("enter first number: "))
b = int(input("enter second number: "))

# Arithmetic operations on two user-input numbers.

print("select the arithmetic operation")
print("1 for addition")
print("2 for subtraction")
print("3 for multiplication")
print("4 for division")

choice = input(f"enter choice 1/2/3/4 : ")

if choice == '1':
  print(f"addition of these numbers is {a+b}")
elif choice == '2':
  print(f"subtraction of these numbers is {a-b}")
elif choice == '3':
  print(f"multiplication of these numbers is {a*b}")
elif choice == '4':
  print(f"division of these numbers is {a/b}")
else:
  print("enter choice 1/2/3/4 for arithmetical operation")
     
enter first number: 20
enter second number: 30
select the arithmetic operation
1 for addition
2 for subtraction
3 for multiplication
4 for division
enter choice 1/2/3/4 : 2
subtraction of these numbers is -10
8. Write a program to demonstrate the use of logical operators.

'''The 'and' operator print only when both the condition follow
   The 'or' operator print when any of the one condition follow
   The 'and' operator reverse the conditions of 'and' and 'or' '''


print("Operation of 'and' operator")

a = int(input("enter value of first number: "))
b = int(input("enter value of second number: "))

if a > 0 and b > 0:
    print("The numbers are greater than 0")
else:
  print("Either one or both of the number is less than 0")

print("Operation of 'or' operator")

d = int(input("enter value of first number: "))
e = int(input("enter value of second number: "))

if d > 0 or e > 0:
  print("Either one or both of the number is greater than 0")
else:
  print("both of the numbers are less than 0")

print("Operation of 'not' operator")

f = int(input("enter value of first number: "))
g = int(input("enter value of second number: "))

if not a >= b:
  print("a is less than or equal to b")
elif not a < b:
  print("a is greater than b")
     
Operation of 'and' operator
enter value of first number: 10
enter value of second number: 20
The numbers are greater than 0
Operation of 'or' operator
enter value of first number: 10
enter value of second number: 0
Either one or both of the number is greater than 0
Operation of 'not' operator
enter value of first number: 0
enter value of second number: 19
a is less than or equal to b
9. Write a Python program to convert user input from string to integer, float, and boolean types.

a = input("enter a value: ")

print("choose 1 for type conversion to integer")
print("choose 2 for type conversion to float")
print("choose 3 for type conversion to bolean")

choice = int(input("enter your choice:- "))

if choice == 1:
  b = int(a)
  print(f"original_value: {a}, updated_value: {b}")
  print(f"original_type: {type(a)}, updated_type: {type(b)}")

elif choice == 2:
  b = float(a)
  print(f"original_value: {a}, updated_value: {b}")
  print(f"original_type: {type(a)}, updated_type: {type(b)}")

elif choice == 3:
  b = bool(a)
  print(f"original_value: {a}, updated_value: {b}")
  print(f"original_type: {type(a)}, updated_type: {type(b)}")

else:
  print("Enter choice among 1/2/3")

     
enter a value: 17
choose 1 for type conversion to integer
choose 2 for type conversion to float
choose 3 for type conversion to bolean
enter your choice:- 2
original_value: 17, updated_value: 17.0
original_type: <class 'str'>, updated_type: <class 'float'>
10. Write code to demonstrate type casting with list elements.

# Convert a list of integers to a list of strings
int_list = [1, 2, 3, 4]
str_list = list(map(str, int_list))
print(f"Original integer list: {int_list}, type: {[type(item) for item in int_list]}")
print(f"Converted string list: {str_list}, type: {[type(item) for item in str_list]}")

# Convert a list of strings (representing numbers) to a list of integers
string_num_list = ["5", "6", "7", "8"]
integer_list = list(map(int, string_num_list))
print(f"Original string number list: {string_num_list}, type: {[type(item) for item in string_num_list]}")
print(f"Converted integer list: {integer_list}, type: {[type(item) for item in integer_list]}")

# Convert a list of integers to a list of floats
another_int_list = [9, 10, 11]
float_list = list(map(float, another_int_list))
print(f"Original integer list: {another_int_list}, type: {[type(item) for item in another_int_list]}")
print(f"Converted float list: {float_list}, type: {[type(item) for item in float_list]}")
     
Original integer list: [1, 2, 3, 4], type: [<class 'int'>, <class 'int'>, <class 'int'>, <class 'int'>]
Converted string list: ['1', '2', '3', '4'], type: [<class 'str'>, <class 'str'>, <class 'str'>, <class 'str'>]
Original string number list: ['5', '6', '7', '8'], type: [<class 'str'>, <class 'str'>, <class 'str'>, <class 'str'>]
Converted integer list: [5, 6, 7, 8], type: [<class 'int'>, <class 'int'>, <class 'int'>, <class 'int'>]
Original integer list: [9, 10, 11], type: [<class 'int'>, <class 'int'>, <class 'int'>]
Converted float list: [9.0, 10.0, 11.0], type: [<class 'float'>, <class 'float'>, <class 'float'>]
11. Write a program that checks if a number is positive, negative, or zero.

taken_number1 = int(input("enter a number: "))

#for the positive number

if taken_number1 > 0:
  print(f"{taken_number1} is a positive number")

#for the negative number

elif taken_number1 < 0:
  print(f"{taken_number1} is a negative number")

#for the zero

else:
  print(f"{taken_number1} is zero")
     
enter a number: 17
17 is a positive number
12. Write a for loop to print numbers from 1 to 10.

for i in range(1, 11):
  print(i)


     
1
2
3
4
5
6
7
8
9
10
13. Write a Python program to find the sum of all even numbers between 1 and 50.

# Python Program: Sum of Even Numbers Between 1 and 50

def sum_even_numbers():
    total = 0
    for number in range(1, 51):
        if number % 2 == 0:
            total += number
    return total

# Display the result
print("Sum of even numbers from 1 to 50 is:", sum_even_numbers())
     
Sum of even numbers from 1 to 50 is: 650
14. Write a program to reverse a string using a while loop.

string = "My name is Roshan Singh"
print(type(string))
print(f"Original string: {string}")


reverse_string = string[::-1]
print(f"reverze string: {reverse_string}")
     
<class 'str'>
Original string: My name is Roshan Singh
reverze string: hgniS nahsoR si eman yM
15. Write a Python program to calculate the factorial of a number provided by the user using a while loop.


try:
    num = int(input("Enter a non-negative integer to calculate its factorial: "))
except ValueError:
    print("Invalid input. Please enter an integer.")
else:
        factorial = 1
        # Initialize a counter for the while loop
        i = 1

        # Use a while loop to calculate the factorial
        while i <= num:
            factorial *= i
            i += 1
        print(f"The factorial of {num} is: {factorial}")

     
Enter a non-negative integer to calculate its factorial: 5
The factorial of 5 is: 120
