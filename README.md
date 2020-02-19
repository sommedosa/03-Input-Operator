# Input, Operator

## Built-in input function reads input from keyboard
* Returns the data as a string
* Format: variable = input(prompt)

## Built-in functions convert between data types
* int(item) converts item to an int
* float(item) converts item to a float
* Nested function call: general format: function1(function2(argument))
  - value returned by function2 is passed to function1
* Type conversion only works if item is valid numeric value, otherwise, throws exception

## Performing Calculations
* Math expression: performs calculation and gives a value
* Math operator: tool for performing calculation
* Operands: values surrounding operator
  - Variables can be used as operands
* Resulting value typically assigned to variable

## Operator  Precedence and Grouping with Parentheses
* Python operator precedence:
  1. Operations enclosed in parentheses
     - Forces operations to be performed before others
  2. Exponentiation (**)
     - Exponent operator (**): Raises a number to a power
  3. Multiplication (*), division (/ and //), and remainder (%)
     - / operator performs floating point division
     - // operator performs integer division
     - % Performs division and returns the remainder
  4. Addition (+) and subtraction (-)
* Higher precedence performed first
  - Same precedence operators execute from left to right

## Mixed-Type Expressions and Data Type Conversion
* Two int values: result is an int
* Two float values: result is a float
* int and float: int temporarily converted to float, result of the operation is a float

## Breaking Long Statements into Multiple Lines
* Multiline continuation character (\): Allows to break a statement into multiple lines
* Any part of a statement that is enclosed in parentheses can be broken without the line continuation character

--------------------

## Exercise3

1. A __________ error does not prevent the program from running, but causes it to produce incorrect results. </br>
   a. syntax </br>
   b. hardware </br>
   c. logic </br>
   d. fatal </br>

2. A(n) __________ is a set of well-defined logical steps that must be taken to perform a task.  </br>
   a. logarithm </br>
   b. plan of action </br>
   c. logic schedule </br>
   d. algorithm </br>

3. An informal language that has no syntax rules and is not meant to be compiled or executed is called __________. </br>
   a. faux code </br>
   b. pseudocode </br>
   c. Python </br>
   d. a flowchart </br>

4. A __________ is a diagram that graphically depicts the steps that take place in a program. </br>
   a. flowchart </br>
   b. step chart </br>
   c. code graph </br>
   d. program graph </br>

5. A __________ is a sequence of characters. </br>
   a. char sequence </br>
   b. character collection </br> 
   c. string </br>
   d. text block </br>

6. Short notes placed in different parts of a program explaining how those parts of the program work are called __________. </br>
   a. comments </br>
   b. reference manuals </br>
   c. tutorials </br>
   d. external documentation </br>

7. A string literal in Python must be enclosed in __________. </br>
   a. parentheses. </br>
   b. single-quotes. </br>
   c. double-quotes. </br>
   d. either single-quotes or double-quotes. </br>

8. This symbol marks the beginning of a comment in Python. </br>
   a. & </br>
   b. * </br>
   c. ** </br>
   d. # </br>

9. Which of the following statements will cause an error? </br>
   a. x = 17 </br>
   b. 17 = x </br>
   c. x = 99999 </br>
   d. x = '17' </br>

10. In the expression 12 + 7, the values on the right and left of the + symbol are called __________. </br>
   a. operands </br>
   b. operators </br>
   c. arguments </br>
   d. math expressions </br>

11. Which built-in function can be used to read input that has been typed on the keyboard? </br>
   a. input() </br>
   b. get_input() </br>
   c. read_input() </br>
   d. keyboard() </br>

**True or False**
1. Variable names can have spaces in them.
2. In Python, the first character of a variable name cannot be a number.
3. If you print a variable that has not been assigned a value, the number 0 will be displayed.
4. In a math expression, multiplication and division take place before addition and subtraction.



**Short Answer**
1. Does the condition "Hello " == "Hello" evaluate to True or False?
2. A common error is to replace the condition (not (n < m)) with the condition (n > m). The correct replacement is (n >= m).
3. Explain why (27 > 9) evaluates to True, whereas (“27” > “9”) evaluates to False.
