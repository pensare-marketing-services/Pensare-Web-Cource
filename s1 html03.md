**Introduction to HTML: Lesson 3 - Building Interactive Forms**

Welcome back to our HTML course! In this lesson, we'll explore how to create interactive forms using HTML. Forms are an essential part of web development as they allow users to input data and interact with your website. Let's dive into the world of forms!

**Understanding HTML Forms**
HTML forms provide a way for users to submit data to a web server. They're commonly used for various purposes, such as user registration, login, surveys, and more. Form elements include input fields, checkboxes, radio buttons, text areas, and buttons.

**Basic Form Structure**
Here's a simple example of an HTML form:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Interactive Form</title>
</head>
<body>
    <h1>Contact Us</h1>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>
        
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

**Form Elements Explained**
- The `<form>` element wraps all the form elements.
- `<label>` elements provide a text description for form controls.
- `<input>` elements are used for text input, email input, and more. The `type` attribute specifies the input type.
- `<textarea>` creates a multi-line text input area.
- The `for` attribute of `<label>` should match the `id` of the corresponding form element for better accessibility.
- The `required` attribute indicates that the field must be filled out before submitting the form.
- The `<button>` element creates a submit button.

**Input Types**
HTML offers various input types, including:
- `text`: Single-line text input.
- `email`: Input for email addresses.
- `password`: For secure password input.
- `checkbox`: Checkboxes for multiple options.
- `radio`: Radio buttons for single-choice options.
- `submit`: A button to submit the form.
- `reset`: A button to reset the form.

**Your Task: Create a Registration Form**
For this lesson's assignment, create an HTML file named `registration.html`. Build a registration form with fields for a user's name, email, password, gender (using radio buttons), and a checkbox for agreeing to terms. Include a submit button to process the form.

**Conclusion**
Congratulations! You've completed the third lesson of our HTML course. You've learned how to create interactive forms using various input elements. Forms are vital for user engagement and data collection on your website. In the next lesson, we'll explore CSS, the language used to style and enhance the appearance of your HTML content. Keep up the excellent work!