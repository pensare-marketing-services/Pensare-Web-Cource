**Introduction to React.js: Lesson 7 - Forms and Controlled Components**

Welcome to the seventh lesson of the "Introduction to React.js" course! In this lesson, we'll explore how to work with forms in React and use controlled components to manage form state.

**Working with Forms**
Forms are a crucial part of user interaction in web applications. React provides a way to manage form input and state using controlled components.

**Controlled Components**
In a controlled component, form elements like inputs and text areas are controlled by React's state. This means that React keeps track of the input's value and updates it through state.

```jsx
import React, { Component } from 'react';

class LoginForm extends Component {
  constructor(props) {
    super(props);
    this.state = {
      username: '',
      password: ''
    };
  }

  handleInputChange = event => {
    const { name, value } = event.target;
    this.setState({ [name]: value });
  };

  handleSubmit = event => {
    event.preventDefault();
    console.log('Form submitted:', this.state.username, this.state.password);
  };

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <input
          type="text"
          name="username"
          value={this.state.username}
          onChange={this.handleInputChange}
        />
        <input
          type="password"
          name="password"
          value={this.state.password}
          onChange={this.handleInputChange}
        />
        <button type="submit">Submit</button>
      </form>
    );
  }
}

export default LoginForm;
```

**Your Task: Signup Form**
For this lesson's assignment, create a SignupForm component that includes fields for a user's name, email, and password. Implement controlled components to manage the form state and create a submission handler that logs the form data when the user submits the form.

**Conclusion**
Congratulations! You've completed the seventh lesson in the "Introduction to React.js" course. You've learned how to work with forms in React and use controlled components to manage form input and state. Controlled components provide a predictable way to handle user input and manage form behavior. In the next lesson, we'll explore React Router, a library for managing navigation in React applications. Keep up the great work on your journey to mastering React.js!