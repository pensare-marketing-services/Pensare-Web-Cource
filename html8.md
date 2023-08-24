**Introduction to HTML: Lesson 8 - Introduction to JavaScript**

Welcome to another exciting lesson in our HTML course! In this lesson, we'll introduce you to the fundamentals of JavaScript, a programming language that enables dynamic and interactive behavior on web pages.

**What is JavaScript?**
JavaScript is a versatile programming language that adds interactivity and dynamic behavior to web pages. It allows you to create responsive user interfaces, handle user input, manipulate the DOM (Document Object Model), and communicate with servers for data retrieval and updates.

**Adding JavaScript to HTML**
You can include JavaScript code in your HTML files using the `<script>` tag. There are two main ways to include JavaScript:
1. **Inline JavaScript:** Embedding the code directly within the HTML file.
2. **External JavaScript:** Linking to an external JavaScript file using the `src` attribute.

**Basic JavaScript Syntax**
JavaScript code consists of statements, which are instructions that the browser can understand. Statements end with a semicolon `;`.

Example of an inline script:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Introduction to JavaScript</title>
</head>
<body>
    <button onclick="alert('Hello, JavaScript!')">Click Me</button>

    <script>
        // Inline JavaScript
        console.log('Hello from JavaScript!');
    </script>
</body>
</html>
```

**Variables and Data Types**
Variables are used to store data values. JavaScript supports various data types such as numbers, strings, booleans, and objects.

```javascript
let name = 'John';
let age = 30;
let isStudent = true;
```

**Functions**
Functions are reusable blocks of code that perform specific tasks. They allow you to organize and modularize your code.

```javascript
function greet(name) {
    console.log('Hello, ' + name + '!');
}

greet('Alice');
```

**DOM Manipulation**
JavaScript can interact with the DOM to modify elements on the page dynamically. You can change text, styles, and even create or delete elements.

```javascript
let paragraph = document.querySelector('p');
paragraph.textContent = 'Updated text!';
```

**Your Task: Adding Interactivity**
For this lesson's assignment, create a new HTML page named `interactivity.html`. Add a button to the page, and when the button is clicked, change the text of a paragraph element using JavaScript. You can also create a function that displays an alert when called.

**Conclusion**
Congratulations! You've completed the eighth lesson of our HTML course. You've taken your first steps into the world of JavaScript, learning about its syntax, variables, functions, and basic DOM manipulation. JavaScript is a powerful tool for adding interactivity and dynamic features to your web pages. In the next lesson, we'll delve deeper into JavaScript and explore conditional statements and loops. Keep up the great work on your web development journey!