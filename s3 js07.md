**Introduction to JavaScript: Lesson 7 - Working with Objects**

Welcome to the seventh lesson in the JavaScript section of our course! In this lesson, we'll explore objects, a versatile and powerful data structure in JavaScript that allows you to represent more complex data.

**Introduction to Objects**
An object is a collection of key-value pairs, where each key is a string (or symbol) and each value can be of any data type.

**Creating Objects**
You can create an object using curly braces `{}` and specifying key-value pairs separated by colons.

```javascript
let person = {
    firstName: "John",
    lastName: "Doe",
    age: 30,
    isStudent: false
};
```

**Accessing Object Properties**
You can access object properties using dot notation or square brackets.

```javascript
console.log(person.firstName); // Output: John
console.log(person["age"]);    // Output: 30
```

**Modifying Object Properties**
You can modify object properties by assigning new values to them.

```javascript
person.age = 31;
console.log(person.age); // Output: 31
```

**Adding and Removing Properties**
You can add new properties to an object or remove existing ones.

```javascript
person.job = "developer";   // Adding a property
delete person.isStudent;    // Removing a property
```

**Objects and Methods**
Objects can also contain functions, which are called methods.

```javascript
let calculator = {
    add: function(a, b) {
        return a + b;
    },
    subtract: function(a, b) {
        return a - b;
    }
};

console.log(calculator.add(3, 5)); // Output: 8
```

**Your Task: Creating an Address Book**
For this lesson's assignment, create a JavaScript program that simulates an address book. Define an object for each contact with properties like name, email, and phone number. Allow the user to add new contacts and display the contacts' details.

**Conclusion**
Congratulations! You've completed the seventh lesson in the JavaScript section. You've learned about objects, a versatile data structure that enables you to represent and manipulate complex data in your programs. Objects are essential for creating organized and structured code. In the next lesson, we'll explore the concept of scope and how it affects the visibility of variables in your code. Keep up the great work on your web development journey!