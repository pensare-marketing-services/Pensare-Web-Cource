**Introduction to React.js: Lesson 3 - State and Lifecycle**

Welcome to the third lesson of the "Introduction to React.js" course! In this lesson, we'll explore the concepts of state and lifecycle methods in React. These concepts are fundamental for building dynamic and interactive user interfaces.

**Understanding State**
State is a way for React components to manage and store data that can change over time. It's essential for creating interactive components that respond to user input and other events.

**Adding State to Class Components**
State can be added to class components using the `state` property. It should be initialized in the constructor.

```jsx
import React, { Component } from 'react';

class Counter extends Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  render() {
    return (
      <div>
        <p>Count: {this.state.count}</p>
        <button onClick={this.increment}>Increment</button>
      </div>
    );
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };
}

export default Counter;
```

**Lifecycle Methods**
Lifecycle methods are special methods that allow you to perform actions at specific points in a component's lifecycle.

- `componentDidMount`: Called after the component is added to the DOM.
- `componentDidUpdate`: Called after the component's update is reflected in the DOM.
- `componentWillUnmount`: Called before the component is removed from the DOM.

**Using Lifecycle Methods**
```jsx
import React, { Component } from 'react';

class Timer extends Component {
  constructor(props) {
    super(props);
    this.state = { seconds: 0 };
  }

  componentDidMount() {
    this.interval = setInterval(this.tick, 1000);
  }

  componentWillUnmount() {
    clearInterval(this.interval);
  }

  tick = () => {
    this.setState({ seconds: this.state.seconds + 1 });
  };

  render() {
    return <p>Seconds: {this.state.seconds}</p>;
  }
}

export default Timer;
```

**Your Task: Timer Component**
For this lesson's assignment, create a Timer component that displays the number of seconds elapsed since the component mounted. Use the `componentDidMount` and `componentWillUnmount` lifecycle methods to start and stop the timer interval.

**Conclusion**
Congratulations! You've completed the third lesson in the "Introduction to React.js" course. You now understand the concepts of state and lifecycle methods in React. State allows components to manage dynamic data, while lifecycle methods enable you to perform actions at specific points in a component's lifecycle. In the next lesson, we'll explore event handling in React. Keep up the great work on your journey to becoming a proficient React developer!