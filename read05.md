JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:


operand1 operator operand2

-----------------------------------------

**Arithmetic operators**

An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).


**Bitwise logical operators**


Conceptually, the bitwise logical operators work as follows:

The operands are converted to thirty-two-bit integers and expressed by a series of bits (zeros and ones). Numbers with more than 32 bits get their most significant bits discarded. For example, the following integer with more than 32 bits will be converted to a 32 bit integer:
Before:

 1110 0110 1111 1010 0000 0000 0000 0110 0000 0000 0001

After: 1010 0000 0000 0000 0110 0000 0000 0001
Each bit in the first operand is paired with the corresponding bit in the second operand: first bit to first bit, second bit to second bit, and so on.
The operator is applied to each pair of bits, and the result is constructed bitwise.

**Logical operators**

Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value

**Loops**

Loops offer a quick and easy way to do something repeatedly. 

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another

**for statement**

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

**do...while statement**

The do...while statement repeats until a specified condition evaluates to false.

statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)

If condition is true, the statement executes again. At the end of every execution, the condition is checked. When the condition is false, execution stops, and control passes to the statement following do...while.

**labeled statement**

A label provides a statement with an identifier that lets you refer to it elsewhere in your program. For example, you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.

**break statement**

Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.