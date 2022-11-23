##Read: 08 - Operators and Loops

##Comparison operators
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

<img width="770" alt="Screenshot 2022-11-17 at 1 39 34 PM" src="https://user-images.githubusercontent.com/118200431/202565448-882c2ba3-2421-493f-b4f2-91cabcdecaa8.png">


##Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

There are also compound assignment operators that are shorthand for the operations listed in the following table:

<img width="705" alt="Screenshot 2022-11-17 at 1 42 06 PM" src="https://user-images.githubusercontent.com/118200431/202565812-86801953-2bf6-4db7-a612-4de122968b40.png">
