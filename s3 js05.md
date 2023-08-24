**Introduction to JavaScript: Lesson 5 - Functions and Modular Code**

Welcome to the fifth lesson in the JavaScript section of our course! In this lesson, we'll dive into functions, an essential concept in programming that allows you to write reusable and organized code.

**Introduction to Functions**
A function is a block of code that performs a specific task. It's designed to be reusable, so you can call it multiple times with different inputs.

**Defining a Function**
You can define a function using the `function` keyword, followed by the function name, parameters, and the code block.

```javascript
function greet(name) {
    console.log("Hello, " + name + "!");
}
```

**Calling a Function**
To execute a function, you need to call it by its name and provide any required arguments.

```javascript
greet("Alice"); // Output: Hello, Alice!
greet("Bob");   // Output: Hello, Bob!
```

**Returning Values**
Functions can also return values using the `return` keyword. This allows you to capture the result of a function and use it elsewhere in your code.

```javascript
function add(a, b) {
    return a + b;
}

let result = add(3, 5); // result will be 8
```

**Function Expressions**
Functions can also be assigned to variables. These are called function expressions.

```javascript
let multiply = function(a, b) {
    return a * b;
};

let product = multiply(4, 6); // product will be 24
```

**Arrow Functions**
Arrow functions provide a more concise syntax for creating functions.

```javascript
let square = (x) => x * x;

let squaredValue = square(5); // squaredValue will be 25
```

**Your Task: Calculator Functions**
For this lesson's assignment, create a JavaScript program that defines functions for basic arithmetic operations: addition, subtraction, multiplication, and division. Allow the user to enter two numbers and choose an operation, then display the result using the corresponding function.

**Conclusion**
Congratulations! You've completed the fifth lesson in the JavaScript section. You've learned about functions, which are vital for writing reusable and modular code. Functions allow you to encapsulate logic, making your code easier to manage and maintain. In the next lesson, we'll explore how to work with arrays, a fundamental data structure in JavaScript. Keep up the great work on your web development journey!