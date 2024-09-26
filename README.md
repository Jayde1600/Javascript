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

27.) Selecting DOM Elements:
    Definition: Selecting DOM elements means targeting specific parts of the HTML document so that they can be manipulated with JavaScript.
    Methods for Selecting Elements:
    getElementById: Selects a single element by its unique id.
    getElementsByClassName: Selects all elements that share the same class name.
    getElementsByTagName: Selects all elements with a specific tag name.
    querySelector: Selects the first element that matches a specified CSS selector.
    querySelectorAll: Selects all elements that match a specified CSS selector.

28.) Common Modifications:
    Changing Content: Use the textContent or innerHTML properties to update the text or HTML inside an element.
    Changing Styles: Use the style property to modify the CSS styles of an element (e.g., element.style.color = "blue";).
    Adding/Removing Classes: Use classList.add, classList.remove, or classList.toggle to manipulate an element’s classes.
    Changing Attributes: Use setAttribute and removeAttribute to modify or remove attributes like src, href, alt, etc.
    Creating and Inserting Elements: Use createElement and appendChild to create new elements and add them to the DOM.

Events:

28.) What Are Events? Definition: An event is an action or occurrence that happens in the browser, such as a user clicking a button, typing in a text field, or scrolling a page. JavaScript can detect these events and respond to them, enabling interactive behavior on web pages.
29.) Event Listeners Definition: Event listeners are functions that wait for a specific event to occur on a particular element. When the event happens, the event listener "listens" for it and triggers a callback function—a function designed to execute when the event occurs.

30.) Attaching Event Listeners:
addEventListener: The most common method for attaching an event listener to an element. It takes two arguments: the event type (e.g., "click", "mouseover", "keydown") and the callback function to execute when the event occurs.

31.) Inline Event Handlers: These can be directly placed within HTML tags (e.g., <button onclick="doSomething()">). However, using addEventListener is preferred as it separates HTML and JavaScript, making code more modular and easier to maintain.

32.) Common Event Types: 
Mouse Events: Triggered by mouse actions. Examples: click, dblclick (double-click), mouseover, mouseout, mousedown, mouseup.
Keyboard Events: Triggered by keyboard actions. Examples: keydown, keyup, keypress.
Form Events: Triggered by form-related actions. Examples: submit, change, focus, blur.
Document/Window Events: Triggered by actions related to the document or window. Examples: load, resize, scroll, DOMContentLoaded.

33.) Event Object:
Definition: When an event occurs, the browser passes an event object to the event handler function. This object contains information about the event, such as the type of event, the element that triggered it, and other details like mouse coordinates for mouse events or key codes for keyboard events. Using the Event Object: The event object can be accessed by adding a parameter to the callback function. This allows the developer to prevent default actions, stop the event from propagating (bubbling up to parent elements), and access event-specific properties.

N O D E  J A V A S C R I P T:

34.) 
HTTP Module:
Purpose: The HTTP module is essential for creating web servers and handling HTTP requests and responses. It allows you to build the backbone of web applications and APIs.
Features: Create and manage web servers, handle different types of requests, and serve responses.

35.) FS (File System) Module:
Purpose: The FS module allows you to interact with the file system, enabling you to read, write, delete, and manipulate files and directories within your Node.js applications.
Features: Perform file operations, manage directories, and handle both synchronous and asynchronous file processing.


