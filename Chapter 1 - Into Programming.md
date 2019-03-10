Chapter 1 - Into Programming
============================
* This is a condensed version of my notes od YDKJS

### Vanilla Javascript Basic Syntax

#### Statements
* A statement is a group of words, numbers and operators that perform a specific task

for example:
```javascript
a = b * 2;
```

#### Expressions
* ```2``` is a literal expression
* ```b``` is a varibale expression
* ```b * 2``` is an arithmetic expression
* ```a = b * 2;``` is an assignment expression

#### Operators (Sourced from MDN)

##### Primary Expressions
Basic keywords and general expressions in Javascript
Symbol | Definition
---| ---
this | The ```this``` keyword refers to a special property of an execution context
function | The ```function``` keyword defines a function expression
class | The ```class``` keyword defines a class expression
function* | The ```function*``` keyword defines a generator function expression
yield | Pause and resume a generator function
yield* | Delegate to another generator function or iterable object
async function | The ```async function``` defines an async function expression
await | Pause and resume an async function and wait for the promise's resolution/rejection
[] | Object initializer/literal syntax
/ab+c/i/ | Regular expression literal syntax
() | Grouping operator 

##### Left Hand Side Expressions
Left values are the destination of an assignment
Symbol | Definition
---| ---
Property accessors | Member operators provide access to a property or method of an object (```(object.property)``` and ```object["property"]```).
```new``` | The ```new``` operator creates an instance of a constructor
new.target | In contructors, ```new.target``` refers to the constructor that was invoked by new
super | The ```super``` keyword calls the parent constructor
```...obj``` | Spread syntax allows an expression to be expanded in places where multiple arguments (for function calls) or multiple elements (for array literals are expected)

##### Increment and Decrement
Postfix/prefix increment and postfix/prefix decrement operators
Symbol | Definition
--- | ---
```A++```| Postfix increment operator
```A--```| Postfix decrement operator
```++A```| Prefix increment operator
```--A```| Prefix decrement operator

##### Unary operators
A unary operation is operation with only one operand
Symbol | Definition
---| ---
```delete``` | The ```delete``` operator delets a property from an object
```void``` | The ```void``` operator discards an expression's return value
```typeof``` | The ```typeof``` operator determines the type of a given object
```+``` | The unary plus operator converts its operand to Number type
```-``` | The unary negation operator converts its operand to Number type and then negates it
```~``` | Bitwise NOT operator
```!``` | Logical NOT operator

##### Arithmetic Operators
Symbol | Definition
---| ---
+ | Addition operator
- | Subtraction operator
/ | Division operator
* | Multiplication operator
% | Remainder operator
** | Exponentiation operator

##### Relational Operators
Symbol | Definition
--- | ---
in | The in operator determines whether an object has a given property
instanceof | The instanceof operator determines whether an object is an instance of another object
< | Less than operator
> | Greater than operator
<= | Less than or equal operator
>= | Greater than or equal operator

##### Equality Operators
The result of evaluating an equality operato is always of boolean based on whether the comparison is true
Symbol | Definition
--- | ---
== | Equality operator
!= | Inequality operator
=== | Identity operator
!== | Nonidentity operator

##### Bitwise shift operators
Symbol | Definition
--- | ---
<< | Bitwise left shift operator
>> | Bitwise right shift operator
>>> | BItwise unsigned right shift operator

##### Binary bitwise operators
Bitwise operators treat their operands as a set of 32 bits (zeros and ones) and return standard javascript numerical values
Symbol | Definition
--- | ---
& | Bitwise AND
&#124; | Bitwise OR
^ | Bitwise XOR
##### Binary logical operators
Logical operators are typically used with boolean (logical) values, and when they are, they return a boolean value.
Symbol | Definition
--- | ---
&& | Logical AND
&#124; &#124;| Logical OR
##### Conditional (ternary) operators
Symbol | Definition
--- | ---
```(condition ? ifTrue: ifFalse)``` | The conditional operator returns one of two values based on the logical value of the condition

##### Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand
Symbol | Definition
--- | ---
= | Assignment operator
&#42;= | Multiplicaiton assignment
/= | Division assignment
%= | Remainder assignment
+= | Addition assignment
-= | Subtraction assignment
<<= | Left shift assignment
>>= | Right shift assignment
>>>= | Unsigned right shift assignment 
&= | Bitwise AND assignment
^= | BItwise XOR assignment
&#124;= | BItwise OR assignment
```[a, b] = [1, 2], {a, b} = {a:1, b:2}``` | Destructuring assignment allows you to assign the properties of an array or object to varibales using syntax that looks similar to array or object literals

##### Comma operator
Symbol | Definition
--- | ---
, | The comma operator allows multiple expressions to be evaluated in a single statement and returns the result of the last expression


























