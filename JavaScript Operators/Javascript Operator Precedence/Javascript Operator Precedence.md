## Javascript Operator Precedence:
Operators have precedence. Precedence defines the order in which the expression will be evaluated. Operators are used to building expression. Expressions are sequences of operators and operands that are evaluated to a single value.

# Operator Precedence from highest to lowest.
 
 `Precedence	Operators`
| Precedence        | Operators           
| ------------- |:-------------
| Highest       |( )
|               |++ — (postfix) new typeof 
|               |++ — (prefix) + – (unary) ! ~ 
|               |* / %
|               |<< >> 
|               |< > <= >= is as 
|               |== != 
|Lowest         |= *= /= %= += -= <<= >>= &= ^= |=
|Higher         |^ 
|               || 
|               |&&
|               ||| 
|               |?: 
|Lower          |&

# The Parenthesis operator always has the highest precedence.
Below is the arithmetic expression.

Example: var a = 100 + 50 * 3; By looking at this example it makes us think whether the result of the above example would be 150*3 or 100+150?
# Which operation will go to execute first? Whether the addition or  the multiplication done first?
As we have already learned in school mathematics rules, multiplication is done first. Multiplication (*) and division ( / ) have higher precedence than addition ( + ) and subtraction ( – ). As soon as we use the parenthesis the precedence gets changed.
# Below are the different types of operators JavaScript supports:
![Operator](https://dotnettutorials.net/wp-content/uploads/2020/02/JavaScript-Operators.png)

# JavaScript Arithmetic Operators with Examples:
Arithmetic operators +, -, *, / are the same as in math. The arithmetic operators are as follows:
# Addition (+) Operator:
This operator adds numbers (Operands). See the following example.

var a = 5;<br>
var b = 2;<br>
var c = a + b;<br>
alert(c);  //7
# Subtraction (-)  Operator:
This operator subtracts the second number (operand) from the first operand. Have a look at the following example.

var a = 5;<br>
var b = 2;<br>
var c = a – b;<br>
alert(c);  //3
# Multiplication (*) Operator:
This operator multiplies operands. Following is an example of Multiplication operator.

var a = 5;<br>
var b = 2;<br>
var c = a * b;<br>
alert(c);  //10
# Division (/) Operator:
This operator divide the numerator number by denominator number. Here is an example of Divison Operator.

var a = 5;<br>
var b = 2;<br>
var c = a / b;<br>
alert(c);  //2.5
# Modulus (%) Operator:
This operator returns the remainder from the division of numbers. The following is an example of modulus operator.

var a = 5;<br>
var b = 2;<br>
var c = a % b;<br>
alert(c);  //1
# Increment (++) Operator
This operator increments numbers by one. Example is given below.

var a = 5;<br>
a++;<br>
var c = a;<br>
alert(c); //6
# Decrement (–) Operator:
This operator decrements numbers by one. The following is an example of decrement operator:

var a = 5;<br>
a–;<br>
var c = a;<br>
alert(c); //4
# Exponentiation (**) Operator
This operator raises the first operand/number to the power of the second operand/number. Please have a look at the following code which is an example of an exponentiation operator.

var a = 5;<br>
var c = a ** 2;<br>
alert(c); //25 i.e. 5**2 =5*5 that is 25.


