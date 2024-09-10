                                                                                                J A V A S C R I P T

Variables:

1.) Variable Definition: A variable in JavaScript is a container that holds data values. Variables allow you to store, update, and manipulate information throughout your code.

2.) Declaring Variables: Each has different characteristics regarding scope and mutability.
var: Has function scope and can be redeclared.
let: Has block scope and can be reassigned but not redeclared within the same scope.
const: Also has block scope, but it cannot be reassigned or redeclared, making it ideal for values that should not change.

3.) Data Types:
Data types in JavaScript define the type of data that a variable can hold. Understanding these types is key to performing correct operations on variables and avoiding errors.

Common Data Types:

Numbers: Used for numeric values (e.g., integers and floating-point numbers).
Strings: A sequence of characters used to represent text.
Booleans: Represents true or false, typically used in conditions and logical operations.
Arrays: A list of values, which can be of any data type, stored in a single variable.
Objects: Complex data structures that can hold multiple values and functions (methods) as properties.

4.) Data Usage: The console.log statements demonstrate how these variables can be used to output their values, illustrating the flexibility of JavaScript variables in handling various types of data.

Operators:

5.) Operators Definition: Operators are symbols or keywords used to perform operations on values (operands). They are the building blocks of expressions in JavaScript.

6.) Types of Operators: Arithmetic Operators: Used for mathematical calculations.
Examples: + (addition), - (subtraction), * (multiplication), / (division), % (modulus), and ** (exponentiation).

7.) Assignment Operators: Used to assign values to variables. Examples: = (assign), += (add and assign), -= (subtract and assign), *= (multiply and assign), /= (divide and assign).

8.) Comparison Operators: Used to compare values and return a boolean (true or false). Examples: == (equal), != (not equal), === (strict equal), !== (strict not equal), > (greater than), < (less than), >= (greater than or equal to), <= (less than or equal to).

9.) Logical Operators: Used to combine multiple conditions. Examples: && (AND), || (OR), ! (NOT).

10.) Unary Operators: Operate on a single operand. Examples: ++ (increment), -- (decrement), typeof (type of operand).

11.) Ternary Operator: A shorthand for an if-else statement.
Example: condition ? expression1 : expression2.

Expressions:

12.) Expressions Definition: An expression is a combination of values, variables, and operators that evaluates to a single value. Expressions can be simple (e.g., a single value or variable) or complex (involving multiple operators and operands).

13.) Types of Expressions:
    Arithmetic Expressions: Use arithmetic operators to perform calculations.
    Example: let total = price * quantity;
    Comparison Expressions: Use comparison operators to evaluate conditions.
    Example: let isAdult = age >= 18;
    Logical Expressions: Combine multiple conditions using logical operators.
    Example: let canVote = (age >= 18) && (citizen === true);

14.) if-else Statements Definition: The if-else statement is a fundamental control structure that executes a block of code if a specified condition is true. If the condition is false, the else block (if provided) is executed instead.

15.) The Structure: if Block: Executes when the condition is true.
                    else if Block: (Optional) checks another condition if the previous one was false.
                    else Block: Executes when none of the previous conditions are met.

16.) if-else can be used multiple times for multiple conditions that have different outcomes.

17.) switch Statements Definition: The switch statement is another control structure used for executing one block of code among many based on the value of an expression. It’s particularly useful when there are many possible conditions to check, and each corresponds to a specific case.

18.)  switch Keyword: Evaluates an expression and matches it to one of several case labels.
      case Labels: Each case contains the code to execute if the expression matches the label.
      break Statement: Stops the execution of more cases after a match is found. Without break, the code will continue executing the subsequent cases (this is called "fall-through").
      default Case: Executes if no matching case is found; it's optional but often used as a fallback.
      Use Case: The switch statement is ideal when you need to compare a single expression against multiple potential values


FUNCTIONS:

19.) Functions Definition: A function is a reusable block of code designed to perform a specific task. Functions allow developers to write code once and use it multiple times, which enhances code efficiency and readability.
20.) Function Declaration: A function can be declared using the function keyword, followed by a name, a list of parameters (optional), and a block of code (the function body).

21.) Parameters and Arguments: Functions can take parameters—values that are passed into the function when it is called. These parameters are used within the function to perform operations. The actual values passed to the function are called arguments.

22.) Return Value: A function can return a value using the return statement. The returned value can then be used elsewhere in the code.

23.) Calling Functions: To execute the code within a function, you call the function by its name, followed by parentheses, optionally passing in arguments.

SCOPE:

24.) Definition: Scope determines the accessibility of variables and functions in different parts of the code. Understanding scope is vital for avoiding errors related to variable accessibility and for writing cleaner, more maintainable code.

25.)Types of Scope:
    Global Scope: Variables declared outside of any function or block have global scope and can be accessed from anywhere in the code.
    Local Scope: Variables declared within a function or block are local to that function or block and cannot be accessed from outside it.
    Function Scope: Variables declared within a function are accessible only within that function.
    Block Scope: Variables declared with let or const within a block ({}) are accessible only within that block.

The DOM (Document Object Model):

26.) Definition: The DOM is a structured representation of an HTML document. It represents the page so that programs can change the document structure, style, and content. JavaScript can be used to manipulate the DOM, enabling developers to dynamically update the content and appearance of web pages.

27.) 










