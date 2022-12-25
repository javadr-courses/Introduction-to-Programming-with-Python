# Introduction-to-Programming-with-Python
This repository contains all jupyter notebook files of `CSQ_IPF22` calss.
You can find the subjects/code-parts/algorithms we've seen in the class easily.

<hr/>

## Table of contents

- [14010801](14010801/14010801.ipynb):
  - Basic usage of built-in functions (such as `print`, `help`, `input`, `len`)
  - `map(int, input().split())` syntax to get multiple input from one line
  - Types of Error: **Syntax error**, **Runtime error** and **Logical error**
  - single-quotation mark and double-quotation mark -- as a way to show strings in python

- [14010807](14010807/14010807.ipynb):
  - `type` function as well as differences between `float`, `int`, `NoneType`, etc.
  - `bin`, `oct`, `hex`, etc.
  - `int() base must be >= 2 and <= 36, or 0`
  - `math` package (`import math`) -- `math.sin`, `math.pi`, `math.e`, `math.tan`, etc.
  - Function definition (how to define a function header, arguments and return value)
  - **fruitful function** versus **void function**
  - `from something import stuff` vs. `import stuff`

- [14010808](14010808/14010808.ipynb):
  - `min`, `max`, `abs` built-in functions
  - `turtle` package and `turtle.Turtle` class
  - **for loop**: `for something in range(number):` syntax (_basic for loop_)
  - Function example: `n_angle`, `square`, `polygon`, `circle`, `arc` and `rectangle` for turtle
  - Set speed of the turtle (using `bob.speed` method)
  - Python `docstring` feature (used for documentations)
  - function definitio: `area` which calculates the area using `math.pi`
  - `bob.shape` method (implemented on `turtle.Turtle` class)

- [14010814](14010814/14010814.ipynb):
  - Several math operators such as `//`.
  - Comparing float numbers using `==` operator is root of error in some cases
    - just check their distance, i.e. `abs(x-y)< 10**-20`
    - `0.1+0.1+0.1 == 0.3` returns `Flase`
  - Boolean values (`True`/`False`), are just integers (`True == 1`, `False == 0`)
  _ All numbers are booleans too (zero is `Flase` and all non-zero is `True`)
  - `if...else`
  - New keyword `pass`
  - Logical-boolean operators (`and`, `or`, `not`)
  - `RecursionError` (by calling `test` function inside of `test` function without any stop-condition)
  - `Recursion` (`Recursive function`)
  - `fact` function as an example of `Recursion` to calculate the factorial

- [14010815](14010815/14010815.ipynb):
  - Reminder for previous session: `fact` function (an example of recursive)
  - `int * str`: `0 * 'string'` results in an empty string with length of 0
  - Checking the depth of Recursion Stack: `test_stack_depth`
  - `map(function, sequence)`
    - `function` will be called on each elements of the `sequence`
    - its usage in getting several inputs in just one lines:
      - `map(int, input().split())`
      - `map(float, input().split())`
  - [**koch snowflake**](https://en.wikipedia.org/wiki/Koch_snowflake): drawing it with `turtle` module; another application of `recursion`

- [14010822](14010822/14010822.ipynb):
  - `typecasting` `float` to `int`; return just the integeral part of number:
    - `int(4.7)` --> `4`
    - `int(-4.7)` --> `-4`
  - Showing that if we convert a `float` value to `int` value, the number after floating-point will be dropped and the result number will become a normal integer.
  - Other `print` function arguments: `end` and `sep`
  - Calculating square root of 2
    - hypotenuse of an isosceles right-angled triangle with the side of 1
    - **Newton Raphson Method**
      - $x_{n+1} = x_n - \frac{f(x)}{f'(x)}$
  - `while` loop
  - `mod` operator (`%`).
  - **Factorial** function:
    - `for` loop
    - `while` loops.
  - **Fibonacci** numbers:
    - `non-recursive` method: `for` loop
    - `recursive` function
    - comparing running time of recursion and non-recursive version

- [14010828](14010828/14010828.ipynb):
  - string
    - slicing `[start[:end:[step]]]`
    - indexing `[index]` or `[-index]`
  - reversing a string:
    - `for` loop
    - slice: `[::-1]`
  - finding a character/substring in a string:
    - with the aid of loops
    - `in` operator
  - `str` methods:
    - `count`
    - `find`
    - `index`
    - `strip`, `lstrip`, `rstrip`
    - `replace`

- [14010905](14010905/14010905.ipynb):
  - Introducing **Algorithms, Flowcharts and Problem solving**.
  - Defining `fact` and `neper` functions and comparing their running time.
  - Defining `birthday` function which shows how to use `.format` method on strings to format float types in a string.
  - Defining `is_complete` function and calculating its running time.
  - Introducing a mathematic formula for `complete` numbers (which is `2**(p-1) * (2**p-1)`, where p is a primary number).
  - Calculating BMI.

- [14010906](14010906/14010906.ipynb):
  - Defining a function called `pi` which calculates and returns the `pi` number using a math formula.
  - Reminder to be careful when doing math operations with `float` types (for example `.1+.1+.1 != .3`).
  - Defining `sum_digit` function which calculates and returns summary of all of the digits inside of an integer (for example `134 --> 1+3+4`).
  - Defining `one_digitizer` function which calls `sum_digit` until the result number has only 1 digit (it's less than 10) using `for loop`.
  - Defining a function called `mehrpooya` which uses a faster, less-expensive and more efficient algorithm to compute the same thing as `one_digitizer` function.
  - Defining `rev_num` function which reverts all digits of a number and returns the result (for example `159 --> 951`).



- [14010912](14010912/14010912.ipynb):
  - Case Studies: Word Play and Lists
  - Showing how to open a file with `open` file (`open('words.txt')`).
  - Using `readlines()` method on an opened file object (`_io.TextIOWrapper`) to get all lines of a file at once as a list.

- [14010913](14010913/14010913.ipynb):
  - 
  - 


</hr>

