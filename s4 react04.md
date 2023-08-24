**Introduction to React.js: Lesson 4 - Handling Events**

Welcome to the fourth lesson of the "Introduction to React.js" course! In this lesson, we'll dive into event handling in React. Events are a crucial part of building interactive user interfaces, and React provides a unified way to manage them.

**Understanding Event Handling**
In React, you handle events similarly to how you would in HTML, but with a few differences. React uses camelCase event names and passes event objects as arguments to event handler functions.

**Handling Click Events**
```jsx
import React, { Component } from 'react';

class Button extends Component {
  handleClick() {
    console.log('Button clicked');
  }

  render() {
    return <button onClick={this.handleClick}>Click me</button>;
  }
}

export default Button;
```

**Passing Arguments to Event Handlers**
```jsx
import React, { Component } from 'react';

class Counter extends Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = (amount) => {
    this.setState({ count: this.state.count + amount });
  };

  render() {
    return (
      <div>
        <p>Count: {this.state.count}</p>
        <button onClick={() => this.increment(1)}>Increment</button>
        <button onClick={() => this.increment(-1)}>Decrement</button>
      </div>
    );
  }
}

export default Counter;
```

**Binding Event Handlers**
If you're using class components, you might need to bind the event handler functions to the component instance using `bind`.

```jsx
import React, { Component } from 'react';

class Input extends Component {
  constructor(props) {
    super(props);
    this.state = { text: '' };
  }

  handleChange(event) {
    this.setState({ text: event.target.value });
  }

  render() {
    return <input value={this.state.text} onChange={this.handleChange.bind(this)} />;
  }
}

export default Input;
```

**Your Task: Click Counter**
For this lesson's assignment, create a ClickCounter component that displays a count of how many times a button has been clicked. Use state to manage the count, and handle the click event on the button.

**Conclusion**
Congratulations! You've completed the fourth lesson in the "Introduction to React.js" course. You now understand how to handle events in React and create interactive user interfaces. Events are essential for building applications that respond to user interactions. In the next lesson, we'll explore conditional rendering in React. Keep up the great work on your journey to mastering React.js!