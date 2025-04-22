# Python-basics
What is Python?
Python is a widely-used, interpreted, object-oriented, and high-level programming language with dynamic semantics, used for general-purpose programming.

And while you may know the python as a large snake, the name of the Python programming language comes from an old BBC television comedy sketch series called Monty Python's Flying Circus.

At the height of its success, the Monty Python team were performing their sketches to live audiences across the world, including at the Hollywood Bowl.

Since Monty Python is considered one of the two fundamental nutrients to a programmer (the other being pizza), Python's creator named the language in honor of the TV show.

## Python goals
In 1999, Guido van Rossum defined his goals for Python:

an easy and intuitive language just as powerful as those of the major competitors;
open source, so anyone can contribute to its development;
code that is as understandable as plain English;
suitable for everyday tasks, allowing for short development times.

## Why Python?

There are many reasons – 

it's easy to learn - the time needed to learn Python is shorter than for many other languages; this means that it's possible to start the actual programming faster;
it's easy to teach - the teaching workload is smaller than that needed by other languages; this means that the teacher can put more emphasis on general (language-independent) programming techniques, not wasting energy on exotic tricks, strange exceptions and incomprehensible rules;
it's easy to use for writing new software - it's often possible to write code faster when using Python;
it's easy to understand - it's also often easier to understand someone else's code faster if it is written in Python;
it's easy to obtain, install and deploy - Python is free, open and multiplatform; not all languages can boast that.

## Starting your work with Python

To start your work, you need the following tools:
•	an editor which will support you in writing the code (it should have some special features, not available in simple tools); this dedicated editor will give you more than the standard OS equipment;
•	a console in which you can launch your newly written code and stop it forcibly when it gets out of control;
•	a tool named a debugger, able to launch your code step-by-step, which will allow you to inspect it at each moment of execution.

# Summary 

1. The print() function is a built-in function. It prints/outputs a specified message to the screen/console window.
2. Built-in functions, contrary to user-defined functions, are always available and don't have to be imported. Python 3.8 comes with 69 built-in functions. You can find their full list provided in alphabetical order in the Python Standard Library.
3. To call a function (this process is known as function invocation or function call), you need to use the function name followed by parentheses. You can pass arguments into a function by placing them inside the parentheses. You must separate arguments with a comma, e.g., print("Hello,", "world!"). An "empty" print() function outputs an empty line to the screen.
4. Python strings are delimited with quotes, e.g., "I am a string" (double quotes), or 'I am a string, too' (single quotes).
5. Computer programs are collections of instructions. An instruction is a command to perform a specific task when executed, e.g., to print a certain message to the screen.
6. In Python strings the backslash (\) is a special character which announces that the next character has a different meaning, e.g., \n (the newline character) starts a new output line.
7. Positional arguments are the ones whose meaning is dictated by their position, e.g., the second argument is outputted after the first, the third is outputted after the second, etc.
8. Keyword arguments are the ones whose meaning is not dictated by their location, but by a special word (keyword) used to identify them.
9. The end and sep parameters can be used for formatting the output of the print() function. The sep parameter specifies the separator between the outputted arguments, e.g., print("H", "E", "L", "L", "O", sep="-"), whereas the end parameter specifies what to print at the end of the print statement.

# What are Literals?
Literals are fixed values directly used in code, like 123 or "Hello".

Example: 123 is a literal (clearly defined value), but c is not.

## Types of Python Literals:
### 1. Integer Literals<br>
Whole numbers without fractions: 123, -456, +789

Readable Format: Use underscores, e.g., 11_111_111

Octal Numbers: Start with 0o (e.g., 0o123 = decimal 83)

Hexadecimal Numbers: Start with 0x (e.g., 0x123 = decimal 291)

### 2. Floating-Point Literals (Floats)<br>
Numbers with decimal parts: 2.5, -0.4, .4, 4.

Use scientific notation for very large/small numbers:

3E8 = 3 × 10⁸ (speed of light)

6.62607E-34 = Planck’s constant

Python auto-formats small/large numbers using e notation for efficiency.

### 3. String Literals<br>
Text enclosed in quotes: "I am a string" or 'Hello'

To include quotes inside strings:

Use escape character (\" or \')

Or use different types of quotes to enclose the string

## Key Notes<br>
Python treats types differently in memory even if they look similar:
4 (int) ≠ 4.0 (float)

Commas cannot be used in numbers (e.g., 11,111 is invalid).

Literals are essential for encoding data in Python programs.

## 4. Boolean Values <br>
Only two Boolean values: True and False

Case-sensitive (true or FALSE will cause an error)

Output of:

print(True > False)  # Output: True
print(True < False)  # Output: False
Because in numeric context: True = 1, False = 0

### SECTION SUMMARY<br>

1. Literals are notations for representing some fixed values in code. Python has various types of literals - for example, a literal can be a number (numeric literals, e.g., 123), or a string (string literals, e.g., "I am a literal.").

2. The binary system is a system of numbers that employs 2 as the base. Therefore, a binary number is made up of 0s and 1s only, e.g., 1010 is 10 in decimal.

Octal and hexadecimal numeration systems, similarly, employ 8 and 16 as their bases respectively. The hexadecimal system uses the decimal numbers and six extra letters.
3. Integers (or simply ints) are one of the numerical types supported by Python. They are numbers written without a fractional component, e.g., 256, or -1 (negative integers).

4. Floating-point numbers (or simply floats) are another one of the numerical types supported by Python. They are numbers that contain (or are able to contain) a fractional component, e.g., 1.27.

5. To encode an apostrophe or a quote inside a string, you can either use the escape character, e.g., 'I\'m happy.', or open and close the string using an opposite set of symbols to the ones you wish to encode, e.g., "I'm happy." to encode an apostrophe, and 'He said "Python", not "typhoon"' to encode a (double) quote.

6. Boolean values are the two constant objects True and False used to represent truth values (in numeric contexts 1 is True, while 0 is False.

Extra  

There is one more, special literal that is used in Python: the None literal. This literal is a NoneType object, and it is used to represent the absence of a value.

# Python Operators Overview <br>
Python can be used like a calculator with the print() function.

## Basic Arithmetic Operators<br>
+ Addition

- Subtraction (also unary minus to change sign)

* Multiplication

/ Division (always returns a float)

// Integer (floor) division – rounds down

% Modulo – gives remainder

** Exponentiation

Rule:

If both operands are integers → result is int

If any operand is float → result is float

## Division by Zero<br>
Always raises an error, including % and //.

## Unary vs Binary Operators<br>
Binary needs two operands (e.g., 5 - 2)

Unary acts on one (e.g., -3, +2)

## Operator Precedence<br>
Determines which operation runs first (like * before +).

Example:
2 + 3 * 5 → 2 + (3 * 5) → 17

🔗 Operator Binding (Associativity)
Most operators: Left-to-right

9 % 6 % 2 → (9 % 6) % 2 → 1

Exponentiation (**): Right-to-left

2 ** 2 ** 3 → 2 ** (2 ** 3) → 256

## Key takeaways<br>

1. An expression is a combination of values (or variables, operators, calls to functions ‒ you will learn about them soon) which evaluates to a certain value, e.g., 1 + 2.

2. Operators are special symbols or keywords which are able to operate on the values and perform (mathematical) operations, e.g., the * operator multiplies two values: x * y.

3. Arithmetic operators in Python: + (addition), - (subtraction), * (multiplication), / (classic division ‒ always returns a float), % (modulus ‒ divides left operand by right operand and returns the remainder of the operation, e.g., 5 % 2 = 1), ** (exponentiation ‒ left operand raised to the power of right operand, e.g., 2 ** 3 = 2 * 2 * 2 = 8), // (floor/integer division ‒ returns a number resulting from division, but rounded down to the nearest whole number, e.g., 3 // 2.0 = 1.0)

4. A unary operator is an operator with only one operand, e.g., -1, or +3.

5. A binary operator is an operator with two operands, e.g., 4 + 5, or 12 % 5.

6. Some operators act before others - the hierarchy of priorities:

the ** operator (exponentiation) has the highest priority;
then the unary + and - (note: a unary operator to the right of the exponentiation operator binds more strongly, for example 4 ** -1 equals 0.25)
then: *, /, and %,
and finally, the lowest priority: binary + and -.
<br>
7. Subexpressions in parentheses are always calculated first, e.g., 15 - 1 * (5 * (1 + 2)) = 0.

8. The exponentiation operator uses right-sided binding, e.g., 2 ** 2 ** 3 = 256.

# Variables

## 1 What are Variables?
Variables in Python act like containers (or boxes) used to store data.

Every variable has:

A name (identifier).

A value (data stored inside).

You can store any type of value: integer, float, string, etc.

Variables are created through assignment, using the = operator.

## Naming Variables
Rules for naming:

Can include letters (a–z, A–Z), digits (0–9), and underscores _.

Must start with a letter or an underscore (not a digit or special symbol).

Case-sensitive (Var and var are different).

Must not be a Python keyword (e.g., import, for, class).

PEP 8 suggests using lowercase and underscores for readability (e.g., my_variable).

## Creating and Using Variables
Assigning a value to a variable automatically creates it.

var = 1
print(var)  # Outputs: 1
Using a variable before assigning a value causes an error.

You can print strings and variables together using +:

version = "3.8.5"
print("Python version: " + version)

## Updating Variables
You can reassign new values to an existing variable:

var = 100
var = var + 1  # var becomes 101
Python’s = means assignment, not equality.

## Mathematical Problem Example
You can use variables to solve problems like the Pythagorean Theorem:

a = 3.0
b = 4.0
c = (a**2 + b**2) ** 0.5
print("c =", c)  # Outputs: 5.0

## Practice Lab: Apples Story
Example task:


john = 3
mary = 5
adam = 6
print(john, mary, adam)
total_apples = john + mary + adam
print("Total number of apples:", total_apples)
Try different values, create new variables, and perform various arithmetic operations (+, -, *, /, //, etc.).

# Purpose of Comments
Comments are notes for humans, not Python.

They're used to:

Explain code functionality.

Describe variable meanings.

Track authorship and version.

Temporarily disable parts of code for testing.

🔹 Syntax of Comments in Python
Begin a comment with a # – everything after it on the line is ignored by Python.

For multi-line comments, start each line with #.

#This is a comment.
#So is this.
Inline comments are also possible:

a = 3.0  # This assigns 3.0 to variable a
🔹 Best Practices
Use clear, self-explanatory variable names (e.g., square_area over aunt_jane).

Avoid unnecessary comments if variable names are self-commenting.

Don’t leave incorrect or outdated comments – they mislead.

🔹 Using Comments to Disable Code
Temporarily turn off lines of code using #, especially useful during debugging/testing.

#y = y + x  #Temporarily disabled for testing
Shortcut: Ctrl + / (Windows) or Cmd + / (Mac) to comment/uncomment multiple lines.

🔹 Improving Code Readability
Use comments where needed, but avoid clutter.

Improve variable names instead of relying only on comments.

Break complex code into functions with meaningful names.

🔹 Section Quiz Insights
Quiz Snippet 1:

#print("String #1")
print("String #2")
✅ Output: String #2 (since the first line is commented out)

Quiz Snippet 2:

#This is
a multiline
comment. #
print("Hello!")
❌ Error – this will cause a SyntaxError because:

a multiline is not commented and isn't valid Python syntax.

# Overview
This section introduces user interaction in Python using the input() function.

You’ll learn to accept user input, convert it to different data types, and use string operators.

🔹 1 The input() function
The input() function reads data entered by the user and returns it as a string.

Basic example:

print("Tell me anything...")
anything = input()
print("Hmm...", anything, "... Really?")
Note: Always store the input in a variable, or the data will be lost.

🔹 2 input() with a prompt
You can pass a string argument to input() to show a prompt:

anything = input("Tell me anything...")

🔹 3 Result of input()
The result of input() is always a string.

Arithmetic operations can’t be done directly on input values unless they are converted.

🔹 4 Prohibited operations
Trying to use a string (from input()) in a math operation causes a TypeError.

anything = input("Enter a number: ")
something = anything ** 2.0  # ❌ TypeError

🔹5 Type Casting
Use int() and float() to convert strings to numeric types:

number = float(input("Enter a number: "))
print(number ** 2)

🔹6 Practical usage
Use type casting with input() to build interactive, numeric programs.

Example: calculating hypotenuse by reading user input.

🔹 7 String Operators
The + operator concatenates strings:

"Hello " + "World"  # → "Hello World"
The * operator repeats strings:

"Hi" * 3  # → "HiHiHi"

🔹8 Converting numbers to strings
Use str() to convert numbers to strings:

str(3.14)  # → "3.14"

🔹 9 LAB: Simple Input and Output
Practice: Accept two numbers and print results of:

Addition

Subtraction

Multiplication

Division

## Key Takeaways:
input() gets string input from the user.

Use int() / float() for numeric conversions.

str() converts data back to strings.

String operators + and * allow concatenation and replication.

# Objective
Learn how to make decisions in Python using conditional statements and comparison operators.

## Key Concepts
1. Decision-Making in Programs
Programs ask questions using comparison operators.

Computers only answer:

True (Yes)

False (No)

2. Equality Operator (==)
Checks if two values are equal.
Example: 2 == 2 → True

= assigns a value; == compares values.

3. Inequality Operator (!=)
Checks if two values are not equal.
Example: 1 != 2 → True

4. Other Comparison Operators
> : Greater than

< : Less than

>= : Greater than or equal to

<= : Less than or equal to

These operators compare values and return either True or False.

5. Using Comparison Results
You can store the result of a comparison in a variable.
Example:

answer = black_sheep > white_sheep
Or you can use it directly in decisions, which will be taught later with if statements.

6. Operator Precedence
Operators like >, <, >=, <= have higher priority than == or !=.

## LAB Exercise 
Task:
Take an integer input n and print True if n >= 100, else print False.
Do not use if statements.

Example Code:

n = int(input())
print(n >= 100)
Sample Output:

Input: 55 → Output: False

Input: 100 → Output: True

# Conditions and Conditional Execution
Conditional statements let Python perform different actions based on whether a condition is True or False.

The basic form is:

if condition:
    # code to run if condition is True
Indentation is crucial—indented code after if is only executed if the condition is true.

Conditions are based on Boolean values (True or False).

if statement:
Executes a block of code only if a given condition is true.

if sheep_counter >= 120:
    sleep_and_dream()
if-else statement:
Handles both scenarios—when the condition is true and when it is false.

if the_weather_is_good:
    go_for_a_walk()
else:
    go_to_a_theater()
Nested if-else:
if statements can be nested inside each other to handle multiple levels of conditions.

if weather_is_good:
    if restaurant_is_open:
        eat_lunch()
    else:
        eat_sandwich()
else:
    if tickets_available:
        go_to_theater()
    else:
        go_shopping()
elif statement:
Short for else if, used for checking multiple conditions in sequence.

if weather_is_good:
    go_for_a_walk()
elif tickets_available:
    go_to_theater()
elif table_available:
    go_for_lunch()
else:
    play_chess()
Only one branch (first True condition) is executed in an if-elif-else cascade.

The else part is optional.

## Analyzing Code Samples
These examples demonstrate practical use of conditional statements to compare numbers:

Example 1 – Find the larger of two numbers

if number1 > number2:
    larger_number = number1
else:
    larger_number = number2
Example 2 – Compact form (single-line)
You can write simple if-else conditions in a single line, though it may reduce readability.

if number1 > number2: larger_number = number1
else: larger_number = number2
Example 3 – Find the largest of three numbers
Begins by assuming the first number is the largest, then checks the other two:

largest = number1
if number2 > largest:
    largest = number2
if number3 > largest:
    largest = number3

## Summary 
Comparison (Relational) Operators:

Used to compare values (e.g., ==, !=, >, <, >=, <=).

Example: If x = 0, y = 1, z = 0, you can use comparisons like x == z (True), x < y (True), etc.

Conditional Statements:

Simple if: Runs the block only if the condition is True.

if x == 10:
    print("x is 10")
Multiple if statements: Each if is checked separately.

if x > 5:
    print("x > 5")
if x == 10:
    print("x is 10")
if-else: Runs one block if True, another if False.

if x < 10:
    print("Less than 10")
else:
    print("10 or more")
if-elif-else: Checks multiple conditions; only the first True block runs.

if x == 10:
    print("x == 10")
elif x > 5:
    print("x > 5")
else:
    print("None")
Nested Conditionals: One if inside another.

if x > 5:
    if x == 10:
        print("nested: x == 10")    

# Introduction to Loops
Loops allow repeated execution of a block of code. Python mainly uses two types of loops:

while loop – Repeats as long as a condition is True.

for loop – Iterates over a sequence or range.

## The while Loop
Syntax:

while condition:
    # loop body
Similar to if, but while continues as long as the condition is true.

Loop must change the condition at some point to avoid infinite loops.

Example: finding the largest number entered by a user until they type -1.

## Infinite Loops
A loop that never ends, e.g.:

while True:
    print("I'm stuck inside a loop.")
Can be exited manually using Ctrl+C.

Often caused by forgetting to update the condition.

## More while Loop Examples
Counting even and odd numbers until user enters 0.

Alternative syntax:

while number != 0:  # same as while number:
if number % 2 == 1: # same as if number % 2:
Using a counter to control loop iterations:

counter = 5
while counter:
    print("Inside the loop", counter)
    counter -= 1
    
## Lab: Guess the Secret Number
A game where the user guesses a secret number.

Uses a while loop to keep asking until correct.

If incorrect: “Ha ha! You're stuck in my loop!”

If correct: print the number and a congratulatory message.

## The for Loop
Used when you know in advance how many times to iterate.

Syntax:

for i in range(100):
    # loop body
range(100) generates values from 0 to 99.

i is the loop control variable.

Example with two arguments:

for i in range(2, 8):  # i takes values from 2 to 7

## Key Takeaways:
Use while when the number of iterations is unknown.

Use for when iterating over a sequence or a set number of times.

Always ensure loop conditions eventually become false (to prevent infinite loops).

Readability > compactness: write clear and understandable loops.

The difference between for loop and while loop in Python lies in how and when they are used:

🔁 for Loop:
Used when the number of iterations is known or you are looping over a sequence (like a list, tuple, string, or range).

Automatically handles the loop variable.

Ideal for counting, iterating through items, or fixed repetitions.

Example:

for i in range(5):
    print(i)
➡️ Prints 0 to 4. Loops exactly 5 times.

🔄 while Loop:
Used when the number of iterations is not known beforehand.

Continues as long as a condition is True.

Needs manual control of the condition (e.g., updating variables inside the loop).

Example:

i = 0
while i < 5:
    print(i)
    i += 1
➡️ Also prints 0 to 4, but you must manage the loop variable (i) yourself.

⚖️ Key Differences:
Feature	                for loop	                                while loop
Iteration control	    Controlled by range() or sequence	        Controlled by a boolean condition
Use case	            Known number of iterations	                Unknown/conditional number of iterations
Loop variable	        Automatically managed	                    Manually updated
Risk of infinite loop	Low (unless looping over infinite range)	High if condition is never False

✅ When to Use:
Use for loop when you know how many times to loop or when iterating over collections.
Use while loop when looping depends on a condition that may vary or be user-controlled.

## More about the for loop and the range() function
The range() function can take 3 arguments: start, stop, and step.

Example: range(2, 8, 3) gives 2 and 5 (it skips by 3 but does not include 8).

If start >= stop, the range is empty.

Loops using empty ranges don't execute.

The range() with 2 arguments must be ascending.

## LAB: Counting Mississippily
Purpose: Simulate counting seconds like "1 Mississippi, 2 Mississippi…".

Uses a for loop from 1 to 5.

Uses time.sleep(1) to pause 1 second between prints.

After counting to 5, it prints: "Ready or not, here I come!"

## The break and continue statements
break: immediately exits the loop.

continue: skips the rest of the current loop iteration and moves to the next one.

These statements simplify code but are not strictly necessary (just syntactic sugar).

Good for handling conditions like exiting early or skipping unwanted data.

## LAB: The break statement – Stuck in a loop
Repeatedly asks user for input until "chupacabra" is entered.

Once matched, prints "You've successfully left the loop." and exits using break.

## LAB: The continue statement – the Ugly Vowel Eater
Asks the user to input a word.

Converts it to uppercase using upper().

Loops through each letter and skips vowels (A, E, I, O, U) using continue.

Prints only the consonants, each on a new line.

## LAB: The continue statement – the Pretty Vowel Eater
Similar to the Ugly Vowel Eater, but instead of printing each consonant:

It collects all consonants into a string word_without_vowels.

At the end, prints that string.

A more refined version of vowel filtering using string concatenation.

## The while loop and the else branch
A while loop can have an else block.

The else block runs after the loop finishes normally (not through break).

Even if the loop doesn't execute at all, the else can still run.

Useful for post-loop operations, especially when no break is used.

## The for loop and the else branch
Just like while, a for loop can also have an else.

The else block executes after the loop finishes without being interrupted by break.

If the loop is not entered at all, the else block still runs.

Demonstrates control variable behavior and flow of execution.

## LAB: Essentials of the while loop – Pyramid Building
Given a number of blocks, build the tallest possible pyramid.

Each level uses 1 more block than the one above.

Use a while loop to subtract blocks and increase the pyramid height.

Stops when not enough blocks are left for the next level.

Example: 6 blocks can build a pyramid of height 3.

# Computer Logic
Python uses logical operators like and, or, and not to form compound conditions.

and: Both conditions must be true.

or: At least one condition must be true.

not: Negates the truth value.

These follow standard truth tables used in logic.

## Logical Expressions
Logical expressions can be simplified using De Morgan’s Laws:

not (A and B) is equivalent to not A or not B

not (A or B) is equivalent to not A and not B

Logical expressions return True or False.

Logical operators do not support the shortcut assignment (op=) form.

## Logical Values vs. Single Bits
Logical operations work on truthiness (0 = False, non-zero = True), not actual bit patterns.

Example: not not 1 is True.

## Bitwise Operators
Bitwise operators work on the binary representation of integers:

& (AND): 1 if both bits are 1.

| (OR): 1 if at least one bit is 1.

^ (XOR): 1 if only one of the bits is 1.

~ (NOT): flips all bits.

Operate on each bit individually, unlike logical operators which evaluate the entire value.

## How Do We Deal with Single Bits?
Use bit masks to check, set, reset, or toggle specific bits:

Check bit: flag_register & mask

Reset bit: flag_register &= ~mask

Set bit: flag_register |= mask

Toggle bit: flag_register ^= mask

Bit masking allows safe manipulation of individual bits without affecting others.

## Binary Left Shift and Binary Right Shift
<< shifts bits left (like multiplying by 2^n).

>> shifts bits right (like integer division by 2^n).

These operations work on integers only.

Example:

17 >> 1 = 8 (equivalent to 17 // 2)

17 << 2 = 68 (equivalent to 17 * 4)

## Section Summary
Logical Operators:

and, or, not – operate on truth values.

Bitwise Operators:

&, |, ~, ^, <<, >> – manipulate individual bits.

Used for tasks like flags, binary calculations, efficient memory handling.

#  Why do we need lists?
In programming, we often need to store multiple values under a single name. Using individual variables (like mark1, mark2, mark3) is inefficient and not scalable.
Lists allow us to store multiple related values in a single variable (like marks = [95, 85, 76]).
This makes it easier to manipulate and process data using loops, instead of writing repetitive code for each variable.
The list is a type of data in Python used to store multiple objects. It is an ordered and mutable collection of comma-separated items between square brackets.
e.g.:my_list = [1, None, True, "I am a string", 256, 0]

## Indexing lists
A list is like a container of elements, and each element has a position called an index, starting from 0.
For example:

colors = ['red', 'blue', 'green']
print(colors[0])  # prints 'red'
We use indexing to access or modify elements in a list.
You can also assign a new value to a specific index like:

colors[1] = 'yellow'  # changes 'blue' to 'yellow'

## Accessing list content
You can:

Access individual elements using indexing.

Print the whole list using print(list_name).

Use len(list_name) to find out how many elements are in the list.
This is useful when looping through a list using for or while.

Example:

colors = ['red', 'blue', 'green']
print(len(colors))  # Output: 3

## Removing elements from a list
You can remove elements using the del statement, which deletes the item at a specific index.

Example:

colors = ['red', 'blue', 'green']
del colors[1]
print(colors)  # ['red', 'green']
Be careful! Once you delete an item, the list shrinks, and accessing a removed index will cause an error.

## Negative indices are legal
Python allows negative indexing, which counts from the end of the list.
For example:

colors = ['red', 'blue', 'green']
print(colors[-1])  # 'green'
print(colors[-2])  # 'blue'
This is helpful when you want to access the last element(s) without knowing the list length.

## LAB – The basics of lists
This was a hands-on activity where you:

Created a list of numbers,

Used indexing to change a value,

Removed a value using del,

Printed the updated list.

Purpose: to practice creating and modifying lists and understanding how changes affect list length and indexing.

## Functions vs. methods
Functions and methods are both callable but differ in how they are used:

A function is a standalone operation like len(list_name).

A method is attached to an object and called using a dot, like list_name.append(value).

So, len() is a function, but append() is a method specific to list objects.

A typical function invocation looks as follows: result = function(arg), while a typical method invocation looks like this:result = data.method(arg).

## Adding elements to a list: append() and insert()
You can add elements in two main ways:

append(value) adds an element to the end of the list.

insert(index, value) adds it at a specific index, shifting other elements.

Examples:

colors = ['red', 'blue']
colors.append('green')  # ['red', 'blue', 'green']
colors.insert(1, 'yellow')  # ['red', 'yellow', 'blue', 'green']

## Making use of lists
Lists are powerful when combined with loops.
You can:

Loop through them using for or while.

Perform operations like sum, count, or modify values.

Example:

numbers = [10, 20, 30]
total = 0
for num in numbers:
    total += num
print(total)  # 60
Using a loop, you can process each element in a clean and efficient way.

## LAB – Using lists
This lab focused on applying list operations in a more practical and problem-solving context.

You were asked to:

Create a list of values (e.g., integers),

Use a loop to iterate through the list,

Possibly apply conditional logic (e.g., find even numbers or sum all values),

Display or process results.

🧠 Purpose: To make you comfortable working with lists dynamically using loops and logic. You got hands-on experience with how lists are used in real programming tasks, like processing datasets or filtering information.

## Slicing
Slicing is a way to access a range of elements in a list using the syntax:

list[start:end]
Important points:

The slice includes the start index but excludes the end index.

If you skip start, it starts from the beginning; if you skip end, it goes till the end.

Examples:

colors = ['red', 'blue', 'green', 'yellow']
print(colors[1:3])   # ['blue', 'green']
print(colors[:2])    # ['red', 'blue']
print(colors[2:])    # ['green', 'yellow']
Slicing is non-destructive, meaning the original list remains unchanged.

## Lists – some simple programs
This section introduced small programs that apply list concepts you’ve learned, such as:

Using append(), insert(), del, slicing, and loops,

Searching for values,

Finding max/min/sum,

Creating new lists based on conditions.

Examples include:

Building a list from user input,

Printing reversed lists using slicing ([::-1]),

Counting specific items,

Removing duplicates, etc.

🧠 Purpose: These programs help solidify your understanding by applying list operations in useful, real-world mini-projects.

# The Bubble Sort

This part introduces the Bubble Sort algorithm:

Goal: Sort a list in increasing order by comparing and swapping adjacent elements if they’re in the wrong order.

Process:

Start from the beginning of the list.

Compare each pair of adjacent elements.

If the first is greater than the second, swap them.

Repeat the process until no more swaps are needed.

After each full pass:

The largest unsorted element "bubbles up" to its correct position (like a bubble rising to the top).

With each new pass, the number of elements to check decreases.

📌 Example:
From [8, 10, 6, 2, 4], each pass pushes the largest remaining value to the end:

1st pass: 10 reaches the end.

2nd pass: 8 moves to its correct place.

Continue until sorted.

## Sorting a List

This part teaches how to implement Bubble Sort in Python and how many passes are needed:

Introduces the concept of using a flag variable swapped to track whether any swaps happened in a pass.

If no swaps happen during a pass, the list is already sorted, and the loop can stop early — making it more efficient.

📌 Example Code:

my_list = [8, 10, 6, 2, 4]
swapped = True

while swapped:
    swapped = False
    for i in range(len(my_list) - 1):
        if my_list[i] > my_list[i + 1]:
            swapped = True
            my_list[i], my_list[i + 1] = my_list[i + 1], my_list[i]
This loops until the list is fully sorted — swapping elements only when necessary.

## The Bubble Sort – Interactive Version

An interactive version of the Bubble Sort is presented here, where:

The user can input values into a list.

The program sorts it using the Bubble Sort technique.

This part emphasizes practical implementation and user interaction in Python.

💡 Important Note:
While learning Bubble Sort is useful to understand basic sorting logic, Python already has built-in sorting functions that are much more efficient and easier to use.

📌 Example using Python’s built-in method:

my_list = [8, 10, 6, 2, 4]
my_list.sort()
print(my_list)  # Output: [2, 4, 6, 8, 10]
🔹 3.5.4 – Section Summary
This wraps up everything taught in Section 5:

## Key Takeaways:

Use the sort() method to quickly sort a list in-place.

lst = [5, 3, 1, 2, 4]
lst.sort()
print(lst)  # [1, 2, 3, 4, 5]
Use the reverse() method to reverse the order of a list.

lst.reverse()
print(lst)  # [4, 3, 2, 1, 0]
💬 You’ve learned:

The logic and step-by-step working of the Bubble Sort algorithm.

How to write it in Python.

That Python offers simpler and faster alternatives (sort(), reverse()).

# Operations on Lists:

## Understanding Lists and Assignments
Assigning one list to another using list_2 = list_1 does not create a copy. Both variables refer to the same memory location.

Changing one will affect the other.

## Slicing Lists
Use slicing to copy lists: list_2 = list_1[:].

General slicing syntax: list[start:end] copies elements from start to end - 1.

Negative indices work just like in regular indexing (e.g., list[1:-1]).

Omitting indices:

list[:end] → from start to end - 1.

list[start:] → from start to end.

list[:] → entire list (deep copy).

## Deleting List Elements
Use del to delete:

specific elements: del list[0]

slices: del list[1:3]

entire list: del list (deletes the variable itself).

## Using in and not in
elem in list → checks if element exists in the list.

elem not in list → checks if element is not in the list.

Returns True or False.

## Simple Programs Using Lists
Find the largest number in a list using a loop.

Search for an element and return its index.

Count matches between two lists (like a lottery result checker).

Remove duplicates from a list:

Create a new list and add items only if not already present.

## Section Summary
Direct assignment shares references.

Use slicing for copying lists or sublists.

Negative and omitted indices make slicing flexible.

Use del to remove list elements or slices.

in and not in help check element presence.

# Lists in Lists (Nested Lists)
Lists can contain other lists as elements.

Example: A chessboard can be modeled as an 8x8 nested list (matrix), with each row being a list of 8 elements.

List Comprehensions simplify list creation.
E.g., row = [WHITE_PAWN for i in range(8)]

## Two-Dimensional Arrays
You can build a full chessboard using nested comprehensions:
board = [[EMPTY for i in range(8)] for j in range(8)]

Access elements using two indices: board[row][column]

You can place pieces by setting specific indices (e.g., board[0][0] = ROOK)

## Multidimensional Lists: Advanced Applications
Useful for representing complex data like weather readings or hotel occupancy.

Example: Store 744 hourly temperature readings for a 31-day month: temps = [[0.0 for h in range(24)] for d in range(31)]

Example operations:

Calculate average noon temp: average = sum(day[11] for day in temps) / 31

Find highest temp: iterate through all temps.

Count hot days: if day[11] > 20.0

3D Example: Hotel with 3 buildings × 15 floors × 20 rooms:
rooms = [[[False for r in range(20)] for f in range(15)] for t in range(3)]

## Section Summary
List Comprehension Syntax:
[expression for item in iterable if condition]

More compact than a standard for loop.

Nested Lists for Matrices: Create and access 2D arrays (e.g., table[0][3])

Multidimensional Lists: Python allows arbitrary levels of nesting (3D arrays and beyond).

# Introduction to Functions

## Why Do We Need Functions?
Functions simplify repetitive tasks, improve code readability, and reduce errors.

Use functions when:

Code is reused multiple times.

Code becomes too complex to manage.

Work needs to be divided among multiple developers (modular design).

## Decomposition
Break complex problems into smaller parts (functions) to improve manageability.

Helps when working in teams: each developer works on different functions or modules.

Supports clarity, testing, and modular development.

## Sources of Functions
Functions can come from:

Built-in functions (e.g., print(), input()).

Preinstalled modules (need to be imported).

User-defined functions (you create them).

Classes (not covered here).

## Your First Function
Define functions using def:
 
def message():
    print("Enter a value:")

It always starts with the keyword def (for define)
next after def goes the name of the function (the rules for naming functions are exactly the same as for naming variables)
after the function name, there's a place for a pair of parentheses (they contain nothing here, but that will change soon)
the line has to be ended with a colon;
the line directly after def begins the function body ‒ a couple (at least one) of necessarily nested instructions, which will be executed every time the function is invoked; note: the function ends where the nesting ends, so you have to be careful.

Functions must be called to execute.

You can reuse the function anywhere in your code.

Modifying the function body updates all instances where it's used.

## How Functions Work
Python reads code top to bottom:

Define functions before calling them.

Avoid naming conflicts (e.g., don’t use same name for a variable and a function).

A function call:

Jumps to the function → runs its body → returns back after execution.

## Section Summary
Functions improve reusability, clarity, and structure.

Python functions:

Built-in

From modules

User-defined

Lambda (covered later)

Define with:

def function_name(parameters):
    # body
Example:

def hello(name):
    print("Hello,", name)
hello("Aastha")

# Understanding Function Communication: Parameters and Arguments
Functions in Python are blocks of code designed to perform specific tasks. They become powerful when they can accept input values (called arguments) to process and produce results based on different conditions. These inputs are handled using parameters.

## Parameterized Functions

Parameters are variables listed inside the parentheses of a function definition.

Arguments are actual values passed to the function when it is called.

### Key Points:

Parameters exist only within the function (local scope).

Arguments are defined outside and are passed to the function during invocation.

def message(number):
    print("Enter a number:", number)

message(1)  # Output: Enter a number: 1
Even if a variable with the same name exists outside the function, it’s different inside. This concept is called shadowing.

## Positional Argument Passing
Arguments are matched to parameters by their position.

The first argument goes to the first parameter, the second to the second, and so on.

def greet(first_name, last_name):
    print("Hello,", first_name, last_name)

greet("John", "Doe")  # Output: Hello, John Doe
📌 This order is crucial! Changing the order changes the meaning.

## Keyword Argument Passing
Arguments are passed using parameter names, so their order doesn’t matter.

greet(first_name="James", last_name="Bond")
greet(last_name="Skywalker", first_name="Luke")
📌 Using incorrect parameter names causes a TypeError.

## Mixing Positional and Keyword Arguments
You can mix both, but:

Positional arguments must come before keyword arguments.

def add(a, b, c):
    print(a + b + c)

add(3, b=2, c=1)  # Correct
add(a=3, 2, c=1)  # ❌ SyntaxError

## Default Parameter Values
You can give a default value to a parameter, making it optional during function calls.

def intro(first_name, last_name="Smith"):
    print("Hello, my name is", first_name, last_name)

intro("James")  # Output: Hello, my name is James Smith
📌 Default values make functions flexible and avoid repetition.

## Summary

Concept	Description
Parameters	Placeholders in function definitions to accept values
Arguments	Actual values passed to parameters when calling a function
Positional Arguments	Matched based on order
Keyword Arguments	Matched by parameter name, order doesn't matter
Default Parameters	Allow functions to have optional arguments
Mixing Rules	Positional must come before keyword arguments

# 🔁 Functions: Effects vs. Results
Functions can produce effects (like printing text) or return results using the return keyword.

return exits the function and can optionally send a result back to the caller.

## Types of return Statements
Without Expression
Ends the function early but doesn't return a specific value (implicitly returns None).

def func():
    if condition:
        return  # Ends here
    print("Continue...")
With Expression
Returns a computed value.

def add(a, b):
    return a + b
    
## The None Value
Special value representing "nothing" or "no result".

Returned by default if no return is specified.

Can't be used in expressions (e.g., None + 2 causes error).

Use is None to check for it.

## Functions & Lists

### Passing a list to a function is allowed:

def sum_list(lst):
    return sum(lst)
## Returning a list from a function is allowed:

def generate_list(n):
    return list(range(n))
    
### Practice LABs Summary
Leap Year Check: Function that returns True if a year is a leap year.

Days in a Month: Function that returns days in a given year-month combo.

Day of the Year: Returns the day number from a date.

Prime Number Checker: Function to verify if a number is prime.

Fuel Consumption Converters:

liters_100km_to_miles_gallon

miles_gallon_to_liters_100km

## Key Takeaways
Use return to send back a value.

You can ignore a function’s return if not needed.

Use None carefully — it often means no value or a mistake.

Lists can be both inputs and outputs of functions.

Function results can be assigned to variables for reuse.

#  What is Scope?
Scope refers to the region of code where a variable is recognized.

Example: A function’s parameter is only accessible inside the function.

## Types of Variables:
Global Variables:

Defined outside functions.

Accessible inside functions unless shadowed by a local variable of the same name.

Local Variables:

Defined inside functions.

Only accessible within the function where they are created.

## Important Rules & Examples:
✅ A global variable can be read inside a function.

python
Copy
Edit
var = 2
def multiply(x):
    return x * var  # uses global var
    
❌ A global variable is not writable inside a function without global:

python
Copy
Edit
var = 2
def change():
    var = 5  # this creates a *new local* var
    
✅ Use global keyword to modify a global variable inside a function:


var = 2
def change():
    global var
    var = 5  # modifies global var
    
## Function Arguments and Scope:
Scalar values (e.g., int, float):

Passed by value (copy of the value).

Changes inside function do not affect the original.

Lists and mutable objects:

Passed by reference.

Reassigning the list creates a new local copy.

Modifying the list (e.g., deleting an item) affects the original.

def modify_list(lst):
    del lst[0]  # this affects the original list
    
## Key Takeaways:
Variables outside a function are accessible inside unless shadowed.

Variables defined inside a function don't exist outside it.

Use global to allow a function to modify a global variable.

Scalars are passed by value, lists are passed by reference.

Reassigning a list doesn’t affect the original, but modifying it does.

# Creating Multi-Parameter Functions
This section introduces the concept of functions with multiple parameters using various real-life examples.

## BMI Calculator
Calculates Body Mass Index using weight / height².

Enhancements include:

Input validation: returns None if weight or height is unrealistic.

Added helper functions to convert imperial units to metric:

lb_to_kg(lb) → Converts pounds to kg.

ft_and_inch_to_m(ft, inch=0.0) → Converts feet & inches to meters.

Final function handles users' height/weight in feet/inches and pounds.

## Triangle Functions
is_a_triangle(a, b, c):

Checks if three lengths can form a triangle using the triangle inequality theorem.

Returns True or False.

is_a_right_triangle(a, b, c):

Uses the Pythagorean theorem to check for right-angled triangles.

Identifies the longest side as the hypotenuse.

area_of_triangle(a, b, c):

Calculates area using Heron’s formula.

Checks if it's a valid triangle before computing.

## Factorial Function
factorial_function(n):

Returns factorial of a non-negative integer.

Uses a for loop for iterative computation.

Returns None if input is negative.

## Fibonacci Sequence
fib(n):

Computes the nth Fibonacci number.

First two numbers are 1, and each next is the sum of the previous two.

Uses a loop for efficiency.

## Recursion
Introduces recursive functions:

A function that calls itself.

Great for problems like factorials and Fibonacci.

Examples show how recursive solutions are often shorter and conceptually aligned with mathematical definitions.

# Tuples and Dictionaries from the Python course:

## Sequence Types and Mutability
Sequence types: Data types that store multiple values in order, e.g., lists and tuples. These can be iterated using for loops.

Mutability:

Mutable objects (like lists) can be modified in place (in situ).

Immutable objects (like tuples) cannot be changed after creation.

## Tuples
Tuples are immutable sequences and are created using parentheses or just commas.

Example: tuple_1 = (1, 2, 3) or tuple_2 = 1., 2., 3.

Can contain elements of different types.

Single-element tuples must include a comma: (1,)

Accessing elements is like lists, but you can’t modify them (append, del, etc. will raise errors).

Tuple operations:

len() – length

+, * – concatenation and repetition

in, not in – membership check

Can be used on the left side of assignment for unpacking values (e.g., swapping variables).

## Dictionaries
Dictionaries are mutable collections of key-value pairs.

Created using curly braces {}.

Example: {"cat": "chat", "dog": "chien"}

Keys must be unique and immutable (strings, numbers, tuples).

Dictionaries are unordered (in older versions of Python).

Access values using keys: dictionary['cat']

Use in / not in to check key existence before accessing.

Helpful formatting: hanging indent for readability.

##  Dictionary Methods
.keys() returns iterable of all keys.

.items() returns key-value pairs as tuples.

Looping through:

for key in d.keys():
    print(key, "->", d[key])
or

for k, v in d.items():
    print(k, "->", v)
Modifying values:
Just assign: d["cat"] = "minou"

## Modifying and Adding Values in Dictionaries

Modifying an Existing Value:
Simply assign a new value to an existing key:

dictionary = {"cat": "chat", "dog": "chien", "horse": "cheval"}
dictionary['cat'] = 'minou'
print(dictionary)
Output:
{'cat': 'minou', 'dog': 'chien', 'horse': 'cheval'}

To sort the dictionary keys, use:

for key in sorted(dictionary.keys()):
    print(key)
Accessing Values:
Use the values() method to get all the values in the dictionary:

for french in dictionary.values():
    print(french)
Adding a New Key-Value Pair:
Add a new pair simply by assigning a value to a new key:

dictionary['swan'] = 'cygne'
print(dictionary)
Output:
{'cat': 'chat', 'dog': 'chien', 'horse': 'cheval', 'swan': 'cygne'}

Alternatively, use the update() method:

dictionary.update({"duck": "canard"})
print(dictionary)
Removing a Key:
Use del to remove a key-value pair:

del dictionary['dog']
print(dictionary)
Output:
{'cat': 'chat', 'horse': 'cheval'}

Trying to remove a non-existing key will cause an error.

Removing the Last Item:
Use the popitem() method to remove and return the last item:

dictionary.popitem()
print(dictionary)
Output:
{'cat': 'chat', 'dog': 'chien'}

In older Python versions (pre-3.6.7), popitem() removes a random item.

##  Using Tuples and Dictionaries Together
Problem Overview:

Collect students' names and scores.

Store names as dictionary keys, and tuples of scores as values.

Input ends when the user enters an empty name.

Calculate and print each student's average score, sorted by name.

Code Breakdown:

Initialize an empty dictionary.

Use a loop to take student names and scores.

If name exists, append new score to the tuple.

If name is new, create a new key with a one-element tuple.

After input ends, iterate through the sorted dictionary and calculate averages.

## Tuples – Key Points
Ordered & Immutable: Like lists but unchangeable.

Declaration:

Empty: ()

One-element: ("one",) or "one",

Indexing: Access elements via indices.

Immutability: Elements can't be modified, but you can delete the whole tuple.

Operations:

Loop through tuples.

Check membership (in / not in).

Use len(), concatenate (+), or repeat (*).

Conversion: Use tuple() to convert other iterables into tuples.

## Dictionaries – Key Points
Unordered (ordered in Python 3.6+), Mutable, with key-value pairs.

Accessing: Use dict[key] or dict.get(key).

Modification: Update values using keys.

Adding/Removing:

Add with assignment or update().

Remove with del, popitem(), or clear().

Loops:

Loop through keys.

Use items() to loop through key-value pairs.

Check Key: Use key in dict to check existence.

Copying: Use copy() to duplicate a dictionary.

# Exceptions
Overview: This section introduces exception handling in Python, helping you manage errors and prevent program crashes. It also covers debugging and testing tips to improve your coding process.

## Errors – The Developer's Reality: 
Errors are inevitable in programming, and even the most careful programmers make mistakes. However, accepting that errors happen can lead to better code quality.

Errors in Data vs. Code:

Errors can occur when the program gets incorrect data (e.g., non-integer input when expecting an integer).

Programming errors (bugs) arise due to mistakes made while writing the code.

## When Data is Not What it Should Be: 
Input errors (e.g., entering non-integer data) cause program failures. Python raises specific error messages, like ValueError, when this happens. It's important to handle such errors effectively to prevent program crashes.

## The Try-Except Block: 
Python’s "better to beg for forgiveness than ask for permission" approach means handling errors when they occur, rather than preventing them beforehand. This is done using the try-except block:

try: Code that may raise an exception.

except: Handles the exception if it occurs.

## The Exception-Proves-the-Rule Approach: 
With try and except, the program doesn't terminate on an error. Instead, control moves to the except block, which handles the error. This approach accepts errors as part of the program flow.

## Dealing with Multiple Exceptions: 
Python allows handling multiple exceptions using multiple except branches. Each branch can handle a different exception type, such as ValueError and ZeroDivisionError, with customized handling for each.

## The Default Exception: 
The default except block catches exceptions not explicitly handled by other branches. This block must always be placed last in the except chain.

## Common Exceptions:

ZeroDivisionError: Occurs when trying to divide by zero (using /, //, or %).

ValueError: Raised when a function receives a valid type but an unacceptable value (e.g., trying to convert a non-numeric string to an integer).

TypeError: Happens when an operation or function is applied to an object of inappropriate type (e.g., using a float as a list index).

AttributeError: Raised when an invalid method is called on an object.

SyntaxError: Occurs when Python detects a grammar error in the code, often only when that specific line is executed. It’s important to fix syntax errors before running the code.

Key Takeaways:
Errors are a normal part of programming, and handling them properly is crucial.

Use try-except blocks to manage exceptions and prevent crashes.

Multiple except branches allow handling different exceptions with specific solutions.

## Testing Your Code: 
It's essential for developers to test their code, as testing does not prove error-free code, but rather helps identify bugs. Developers often can't objectively evaluate their own work, which is why testing is crucial. Testers help in finding bugs that developers may overlook.

## Execution Paths: 
When testing, ensure all possible execution paths of the code are covered (e.g., if-elif-else statements). This ensures all scenarios, like positive, negative, and zero values, are considered during testing.

## Unseen Errors: 
Python, being an interpreted language, may not catch certain errors if those parts of the code are not executed during testing (e.g., if there's a typo in an unexecuted function). This is why covering all paths in tests is vital.

## Debugging:
Debugging is the process of finding and fixing bugs, typically done using a debugger. It allows developers to inspect the state of variables and step through the code. If using an IDE like IDLE, a debugger can be activated to assist with this process.

## Print Debugging: 
One of the simplest debugging techniques is print debugging, where you insert print() statements to trace the flow of the code and check variable values. However, these should be removed after debugging to avoid confusion for users and testers.

## Helpful Tips for Debugging:

Explain your code to someone else, as this often helps identify the issue.

Isolate the problematic part of the code and test it separately.

Take breaks and come back with a fresh perspective.

Use "Rubber Duck Debugging," where explaining the problem aloud to an inanimate object helps clarify the issue.

Unit Testing: Unit testing is an essential practice in which tests are an integral part of the code. It ensures that changes in the code don't break functionality. Python’s unittest module supports automated testing.

## Python Exceptions:

Syntax Errors occur when the code structure is incorrect.

Exceptions occur during execution, such as ZeroDivisionError or ValueError.

You can handle exceptions using try-except blocks, which help prevent the program from crashing.

Multiple exceptions can be handled within a single try-except block, and specific exceptions should be handled first before general ones.

## Key Python Exceptions: 
Some important exceptions include ZeroDivisionError, ValueError, TypeError, AttributeError, and SyntaxError. Handling exceptions properly is crucial for ensuring smooth execution of your program.

## Final Advice: 
Always test and debug your code carefully. Use various debugging techniques and take breaks if needed. Ensure all paths are covered in your tests, and don't shy away from using tools like debuggers or print() statements to troubleshoot issues.
