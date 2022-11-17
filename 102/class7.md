###Read: 07 - Programming with JavaScript

The control flow is the order in which the computer executes statements in a script.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

*if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}*

JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

#Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}


##Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

-When an event occurs (when a user clicks a button)
-When it is invoked (called) from JavaScript code
-Automatically (self invoked)

##Function Return

*let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}*


###JavaScript Operators


1)The Assignment Operator (=) assigns a value to a variable.
2)The Addition Operator (+) adds numbers:
3)The Multiplication Operator (*) multiplies numbers.

###Types of JavaScript Operators
There are different types of JavaScript operators:

-#Arithmetic Operators

Arithmetic Operators are used to perform arithmetic on numbers:
Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement


-#Assignment Operators

JavaScript Assignment Operators
Assignment operators assign values to JavaScript variables.

The Addition Assignment Operator (+=) adds a value to a variable.

##Operator	Example	Same As
=	x = y	x = y
+=	x += y	x = x + y
-=	x -= y	x = x - y
*=	x *= y	x = x * y
/=	x /= y	x = x / y
%=	x %= y	x = x % y
**=	x **= y	x = x ** y

#Adding Strings and Numbers
#Adding two numbers, will return the sum, but adding a number and a string will return a string:



-#Comparison Operators

##JavaScript Comparison Operators
Operator	Description
==	equal to
===	equal value and equal type
!=	not equal
!==	not equal value or not equal type
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to
?	ternary operator

-#Logical Operators
-#Conditional Operators
-#Type Operators

