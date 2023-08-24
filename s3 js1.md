**Introduction to JavaScript: Lesson 1 - Getting Started with JavaScript**

Welcome to the JavaScript section of our course! By completing the HTML and CSS courses, you've gained a strong foundation in building structured web pages and styling them beautifully. Now, it's time to add interactivity and functionality to your web projects using JavaScript.

**Understanding JavaScript**
JavaScript is a versatile programming language that allows you to add dynamic behavior to your web pages. It's commonly used for tasks like form validation, user interaction, animations, and more.

**Adding JavaScript to Your Web Pages**
You can include JavaScript code in your HTML documents using the `<script>` tag. Place your JavaScript code either within the `<head>` section or just before the closing `</body>` tag for better performance.

```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Example</title>
    <script>
        // Your JavaScript code goes here
    </script>
</head>
<body>
    <!-- HTML content here -->
</body>
</html>
```

**Basic JavaScript Concepts**
- **Variables:** Use variables to store and manage data. Variables are declared using the `let` or `const` keywords.
- **Data Types:** JavaScript has various data types, including numbers, strings, booleans, arrays, objects, and more.
- **Operators:** Operators like `+`, `-`, `*`, `/`, and `%` are used for arithmetic operations. The `===` operator is used for equality comparison.
- **Functions:** Functions are blocks of code that can be defined and called to perform specific tasks.
- **Conditional Statements:** Use `if`, `else if`, and `else` statements to create decision-making logic.
- **Loops:** Loops like `for` and `while` allow you to repeat code execution.

**Your First JavaScript Code**
Let's write a simple JavaScript code snippet that displays a message when a button is clicked:

```html
<!DOCTYPE html>
<html>
<head>
    <title>First JavaScript Example</title>
    <script>
        function showMessage() {
            alert("Hello, JavaScript!");
        }
    </script>
</head>
<body>
    <button onclick="showMessage()">Click Me</button>
</body>
</html>
```

**Your Task: Interactive Button**
For this lesson's assignment, create a new HTML page with a button. When the button is clicked, change the text of the button to display a greeting.

**Conclusion**
Congratulations! You've completed the first lesson in the JavaScript section. You've learned how to add JavaScript to your web pages and create basic interactive functionality. JavaScript is a powerful tool that enables you to add dynamic behavior and interactivity to your projects. In the next lesson, we'll dive deeper into JavaScript variables, data types, and basic operations. Keep up the great work on your web development journey!