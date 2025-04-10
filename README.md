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


