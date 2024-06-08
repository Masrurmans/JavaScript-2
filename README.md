# In JavaScript we have 3 important topics 
 - Conditions    
 - Loops
 - Functions

 ## And Today we will learn => Condition & Function
 - CONDITION
### Condition IF/ELSE Statement
````````js
if (condition) {
    // code that will be executed if condition is true
} else {
    // code that will be executed if condition is false
}
````````````
IF-ELSE: if the condition is true, then the block of code inside the IF statement is executed; otherwise, the block of code inside the ELSE is executed.

--------------------------

### Condition Ternary Operator
``````
condition ? expression1 : expression2
````````

``````js
var age = 20;
var status = (age >= 18) ? "adult" : "minor";
console.log(status); // Output: adult
`````````

It helps to think of the ternary operator as a shorthand way or writing an if-else statement.

---------------------------

### Condition Switch Statment
``````````js
var day = "Monday";
switch (day) {
  case "Monday":
    console.log("It's Monday!");
    break;
  case "Tuesday":
    console.log("It's Tuesday!");
    break;
  // More cases can be added here
  default:
    console.log("It's not Monday or Tuesday.");
}
``````````````````````

A switch statement is a selection statement that lets you transfer control to different statements within the switch body depending on the value of the switch expression.

-----------------------------

### Loop for / while / do
```````js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
``````````````````

The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

---------------------------

 - FUNCTION
## There are 3 ways of writing a function in JavaScript
### 1.Function Declaration
### 2.Function Expression
- Arrow fanction
- Annonymous function
### 3.Immediately Invoked Function Expression (IIFE)

--------------------------------

### Function Declaration
``````js
function functionName(parameters) {
  // code block to be executed
}
```````````````````

A function identifier preceded by its return type and followed by its parameter list is called a function declaration or function prototype. The prototype informs the compiler of the format and existence of a function prior to its use.

------------------------------------------------

### Function Expression
````````js
var functionName = function(parameters) {
  // code block to be executed
};
````````````````````

Functions are values. They can be assigned, copied or declared in any place of the code. If the function is declared as a separate statement in the main code flow, that's called a “Function Declaration”. If the function is created as a part of an expression, it's called a “Function Expression”.

-----------------------------------------

### Function (IIFE)
``````js
(function(x, y) {
  console.log(x + y);
})(2, 3); // Output: 5
````````````````

A JavaScript IIFE (Immediately Invoked Function Expression) is a function that runs the moment it is invoked or called in the JavaScript event loop. Having a function that behaves that way can be useful for several use cases.

