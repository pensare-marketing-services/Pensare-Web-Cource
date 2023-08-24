**Introduction to HTML: Lesson 9 - Conditional Statements and Loops in JavaScript**

Welcome back to our HTML course! In this lesson, we'll dive deeper into JavaScript by exploring conditional statements and loops, essential concepts that allow you to control the flow of your code and perform repetitive tasks.

**Conditional Statements**
Conditional statements allow you to make decisions in your code based on certain conditions. The most common conditional statement is the `if` statement.

```javascript
let age = 18;

if (age >= 18) {
    console.log('You are an adult.');
} else {
    console.log('You are a minor.');
}
```

You can also use the `else if` clause to handle multiple conditions.

**Logical Operators**
Logical operators (`&&`, `||`, `!`) are used to combine multiple conditions and create more complex logical expressions.

```javascript
let isStudent = true;
let isWorking = false;

if (isStudent && !isWorking) {
    console.log('You are a student not working.');
}
```

**Loops**
Loops allow you to repeat a block of code multiple times. The two most common types of loops are the `for` loop and the `while` loop.

```javascript
// Example of a for loop
for (let i = 0; i < 5; i++) {
    console.log('Iteration ' + i);
}

// Example of a while loop
let counter = 0;
while (counter < 3) {
    console.log('Counter: ' + counter);
    counter++;
}
```

**Array Iteration**
Arrays are often used with loops to iterate through their elements.

```javascript
let fruits = ['apple', 'banana', 'orange'];

for (let fruit of fruits) {
    console.log(fruit);
}
```

**Your Task: Interactive Quiz**
For this lesson's assignment, create an interactive quiz using HTML and JavaScript. Create a set of questions and multiple-choice answers. Use conditional statements to check the user's selected answer and display a message indicating whether the answer is correct or incorrect. You can use `prompt` to gather user input.

**Conclusion**
Well done! You've completed the ninth lesson of our HTML course. You've gained a solid understanding of conditional statements and loops in JavaScript, allowing you to create dynamic and responsive code. These concepts are crucial for building interactive web applications. In the next lesson, we'll explore how to work with JavaScript functions in more depth. Keep up the great work on your web development journey!