**Introduction to JavaScript: Lesson 3 - Conditional Statements and Control Flow**

Welcome to the third lesson in the JavaScript section of our course! In this lesson, we'll delve into conditional statements and control flow, which allow your programs to make decisions and execute different actions based on conditions.

**Conditional Statements**
Conditional statements are used to make decisions in your code. They allow you to execute different blocks of code based on whether a condition is true or false.

**The if Statement**
The `if` statement is the simplest form of a conditional statement. It executes a block of code only if a specified condition evaluates to `true`.

```javascript
let temperature = 25;

if (temperature > 20) {
    console.log("It's a warm day!");
}
```

**The if-else Statement**
The `if-else` statement allows you to execute one block of code when a condition is true and a different block when the condition is false.

```javascript
let age = 16;

if (age >= 18) {
    console.log("You're an adult.");
} else {
    console.log("You're a minor.");
}
```

**The else if Statement**
You can use the `else if` statement to check multiple conditions in a sequence.

```javascript
let grade = 85;

if (grade >= 90) {
    console.log("A");
} else if (grade >= 80) {
    console.log("B");
} else if (grade >= 70) {
    console.log("C");
} else {
    console.log("D");
}
```

**Logical Operators**
Logical operators (`&&` for "and", `||` for "or", `!` for "not") allow you to combine conditions and create more complex decision-making logic.

**Your Task: Weather Check**
For this lesson's assignment, create a JavaScript program that prompts the user for the current weather condition (rainy, sunny, cloudy). Based on the input, display a message that suggests an activity. For example, if it's rainy, suggest staying indoors.

**Conclusion**
Congratulations! You've completed the third lesson in the JavaScript section. You've learned about conditional statements and control flow, which are essential for making decisions and creating dynamic behavior in your programs. In the next lesson, we'll explore loops, a powerful tool for repeating code execution. Keep up the great work on your web development journey!