**Introduction to JavaScript: Lesson 4 - Loops and Iteration**

Welcome to the fourth lesson in the JavaScript section of our course! In this lesson, we'll explore loops and iteration, which are essential for repeating actions and processing data efficiently in your programs.

**Introduction to Loops**
Loops allow you to execute a block of code repeatedly until a certain condition is met. They are especially useful for performing repetitive tasks and iterating over collections of data.

**The for Loop**
The `for` loop is a common loop structure that consists of an initialization, a condition, and an increment or decrement expression.

```javascript
for (let i = 0; i < 5; i++) {
    console.log("Iteration #" + i);
}
```

**The while Loop**
The `while` loop continues to execute a block of code as long as a specified condition evaluates to `true`.

```javascript
let count = 0;

while (count < 3) {
    console.log("Count: " + count);
    count++;
}
```

**The do-while Loop**
The `do-while` loop is similar to the `while` loop, but it ensures that the block of code is executed at least once before checking the condition.

```javascript
let userAnswer;

do {
    userAnswer = prompt("Do you want to continue? (yes/no)");
} while (userAnswer === "yes");
```

**Looping Through Arrays**
Loops are often used to iterate through arrays and perform operations on each element.

```javascript
let numbers = [1, 2, 3, 4, 5];

for (let i = 0; i < numbers.length; i++) {
    console.log("Number: " + numbers[i]);
}
```

**Your Task: Multiplication Table**
For this lesson's assignment, create a JavaScript program that prompts the user for a number and displays the multiplication table for that number using a `for` loop.

**Conclusion**
Congratulations! You've completed the fourth lesson in the JavaScript section. You now understand loops and iteration, which are crucial for repeating tasks and efficiently processing data in your programs. Loops are essential tools for automating repetitive actions and managing collections of information. In the next lesson, we'll explore functions, which allow you to organize and reuse code. Keep up the great work on your web development journey!