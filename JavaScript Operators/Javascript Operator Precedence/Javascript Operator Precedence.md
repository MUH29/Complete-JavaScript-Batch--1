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