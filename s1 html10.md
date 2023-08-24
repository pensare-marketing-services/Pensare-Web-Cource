**Introduction to HTML: Lesson 10 - Working with JavaScript Functions**

Welcome back to our HTML course! In this lesson, we'll delve deeper into JavaScript functions. Functions are a powerful tool that allow you to encapsulate blocks of code for reusability and organization.

**Creating Functions**
A function is a block of code that can be called and executed whenever needed. You can create functions using the `function` keyword.

```javascript
function greet(name) {
    console.log('Hello, ' + name + '!');
}

greet('Alice');
```

**Function Parameters and Return Values**
Functions can accept parameters (input values) and return values (output values). Parameters are placeholders for the values you pass into a function, while the `return` statement is used to send a value back to the caller.

```javascript
function addNumbers(a, b) {
    return a + b;
}

let sum = addNumbers(5, 3);
console.log('Sum: ' + sum);
```

**Anonymous Functions and Arrow Functions**
You can also create functions without giving them a name, known as anonymous functions. Arrow functions provide a concise syntax for creating functions.

```javascript
// Anonymous function
let greet = function(name) {
    console.log('Hello, ' + name + '!');
};

// Arrow function
let multiply = (a, b) => a * b;
```

**Scope and Closure**
Variables declared inside a function are scoped to that function. JavaScript follows a concept called "lexical scoping," which means functions can access variables from their containing (parent) functions.

**Callbacks and Higher-Order Functions**
Functions can be passed as arguments to other functions, allowing you to create more flexible and reusable code patterns. Functions that accept other functions as arguments are called higher-order functions.

**Your Task: Building a Calculator**
For this lesson's assignment, create a simple calculator using HTML, CSS, and JavaScript. The calculator should have buttons for numbers, operators, and an equal sign. When the equal sign is clicked, the calculator should evaluate the expression and display the result. Use functions to handle calculations.

**Conclusion**
Congratulations! You've completed the tenth lesson of our HTML course. You've gained a solid understanding of JavaScript functions and how they can be used to encapsulate and organize code for reusability. Functions are a fundamental concept in programming, and they enable you to create more efficient and modular code. In the next lesson, we'll introduce you to the concept of objects and how they can be used in JavaScript. Keep up the excellent work on your web development journey!