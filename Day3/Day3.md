# Day3

**1.) Expressions: -** In JavaScript, an expression is a piece of code that returns a value. It can be a literal value (such as a number or string), a variable, or a more complex combination of values, variables, and operators that performs some operation and returns a result.

For example, the following are all expressions in JavaScript:

1 + 2 (returns the value 3)

"Hello, " + "world!" (returns the string "Hello, world!")

x * y (returns the product of the variables x and y)

**2.) Operators:-** In JavaScript, an operator is a special symbol used to perform operations on operands (values and variables). For example, 2 + 3; // 5. Here + is an operator that performs addition, and 2 and 3 are operands.

**3.) Types of operators:-**

- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
- BigInt operators
- String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operators

**4.) Conditional expressions:-**

A conditional expression is a statement that evaluates to either true or false and based on that value, it executes a certain block of code.

A conditional expression is also known as a ternary operator because it takes three operands: a condition, a consequence, and an alternative.

**5.) Conditional statements:-**

**6.) Types of conditional statements:-**

- if statement
- if else statement
- if.. else if..else statement
- Switch statement

**7.) Use of prompt and alert in js**

**8.) Way to convert string to number in js**

**9.) Way to convert number to string in js.**

**10.) Concept of condition, consequence, and alternative in js:-**

In JavaScript, the condition, consequence, and alternative are three operands used in a conditional expression, also known as a ternary operator.

The syntax for a conditional expression using the ternary operator is as follows:

Code:

(condition) ? consequence: alternative

The condition is a Boolean expression that is evaluated to be either true or false. If the condition is true, then the consequence is executed and its value is returned. If the condition is false, then the alternative is executed and its value is returned.

Here's an example of how you can use a conditional expression in JavaScript:

Code:

let x = 10;

let y = 20;

let max = (x > y) ? x : y;

console.log(max); // Output: 20

In the example above, the condition is x > y, which is false because x is equal to 10 and y is equal to 20. Therefore, the value of max is the alternative value of y, which is 20.