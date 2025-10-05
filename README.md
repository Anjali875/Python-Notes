# Python-Notes
-Simple and easy, close to English. -Great as first programming language. -Readable like pseudocode. -Course is concise but covers all basics and advanced parts.
-Single-line: #     -Multi-line: """ comment """. -Ctrl+/ to toggle comment in VS Code. -Comments improve readability.
Variable = name for memory location. -Data types: int, float, str, bool, NoneType. 
Operators in Python -Arithmetic: + - * / // % **. -Assignment: =, +=, -=, *=, /=. -Comparison: == != > < >= <= (returns boolean). -Logical: and, or, not. 
Type Function and Casting -type() → check variable type. -Casting: int(), float(), str(). -Invalid casts cause errors.
In Python, REPL stands for Read-Eval-Print Loop. It is an interactive programming environment that allows you to execute Python code one line or block at a time and see the results immediately. This is particularly useful for testing, debugging, or learning Python.
This little Python program uses the pyttsx3 library, which is a text-to-speech conversion library in Python: 
import pyttsx3 
engine = pyttsx3.init() 
engine.say("go study!") 
engine.runAndWait()
string is a sequence of characters enclosed in quotes. it can be sliced for getting a part of string, that is called 'String slicing'.
Index in a string starts from 0 (for backwards, it starts from -1).
Syntax for string slicing= s1= name[ind_start:ind_end]
slicing with skip value: 
eg: word= "amazing"
word[1:6:2] #"mzn"
Changes to existing string can't be done.
'str' object does not support item assignment.
strings are immutable.
Lists are a container to store a set of values of any data type.
They are various list methods:
eg: L1=[1,7,5,4,3,23]
L1.sort= Sorts the elements of the list in ascending order
L1.reverse= Simply reverses the order of the list
L1.append= Adds a new element at the end of the list.
L1.insert= inserts an element at a specific position in the list.
L1.pop= Removes an element from a specific position (index).
L1.remove= Removes the first occurrence of the element x from the list (by value, not index).
A dictionary is used to store data in key–value pairs.
eg: student = {
    "name": "Anjali",
    "age": 19,
    "course": "Computer Science"
}
-Data is stored as key: value pairs  -Keys are unique, values can repeat.
-they are Mutable
Common dictioary methods:
dict.keys(), dict.values(), dict.items(), dict.update({key:value}), dict.pop(key), etc.
A set is a collection of unique and unordered elements. eg: set_name = {element1, element2, element3}
Characteristics:   -No duplicates   -Unordered    -Unindexed    -Mutable (can add/remove items)
Methods:
set.add(x)=Adds an element	
set.remove(x)=Removes element 
set.discard(x)=Removes element 
set.pop()=Removes a random element
set.clear()
Conditional Expressions -if, elif, else with indentation. -if-elif-else ladder vs. independent ifs. -Relational + logical operators with conditions. -in keyword for membership
Loops in python:
Primarily there are two types of loops in python.
while loops & for loops
WHILE LOOP:
In while loops the condition is checked first. If it evaluates to true, the body of the loop is executed otherwise not!
If the loop is entered, the process of (condition check & execution] is continued until the condition becomes False.
Note: If the condition never become false, the loop keeps getting executed.
FOR LOOP:
A for loop is used to iterate through a sequence like list, tuple, or string [iterables]
RANGE FUNCTION IN PYTHON: The range() function in python is used to generate a sequence of number.
We can also specify the start, stop and step-size as follows:
FOR LOOP WITH ELSE: An optional else can be used with a for loop if the code is to be executed when the loops exhausts.
Nested Loops (Loop inside a Loop): You can put one loop inside another.
➤ Example:
for i in range(1, 4):
    for j in range(1, 3):
        print(i, j)
FUNCTION:
A function is a block of code that performs a specific task and can be reused multiple times. It helps make code organized, reusable, and readable. When a program gets bigger in size and its complexity grows, it gets difficult for a program to keep track on which piece of code is doing what! 
EXAMPLE AND SYNTAX OF A FUNCTION:
def func1():
print('hello')
This function can be called any number of times, anywhere in the program.
FUNCTION CALL: Whenever we want to call a function, we put the name of the function followed by parentheses as follows:
func1() # This is called function call.
FUNCTION DEFINITION: The part containing the exact set of instructions which are executed during the function call.
RECURSION:
Recursion is when a function calls itself directly or indirectly. It’s often used to solve problems that can be broken into smaller sub-problems.
Every recursive function must have a base condition to stop itself. Otherwise, it will run forever and cause an infinite loop (error).
FILE I/O:
The random-access memory is volatile, and all its contents are lost once a program terminates in order to persist the data forever, we use files.
A file is data stored in a storage device. A python program can talk to the file by reading content from it and writing content to it.
TYPE OF FILES:
1. Text files (.txt, .c etc)
2. Binary files (.jpg, .dat, etc)
Python has a lot of functions for reading, updating, and deleting files.
OOP IN OYTHON:
-Class = blueprint, Object = instance. -Class vs. instance attributes. -self → refers to object. -Static methods (@staticmethod). -init constructor for initialization. -Inheritance: single, multiple, multilevel. -super() → call parent methods. -Operator overloading (+ etc.). -Property decorators for getters/setters.
