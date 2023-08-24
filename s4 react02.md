**Introduction to React.js: Lesson 2 - Components and Props**

Welcome to the second lesson of the "Introduction to React.js" course! In this lesson, we'll explore components, the fundamental building blocks of React applications. We'll also learn about props, which allow you to pass data between components.

**Understanding Components**
Components are the key to building reusable and modular user interfaces in React. A component is a JavaScript function or class that returns a piece of user interface, which can be rendered to the screen.

**Creating Functional Components**
Functional components are simple JavaScript functions that return JSX. They're the most basic type of component.

```jsx
import React from 'react';

function Greeting() {
  return <h1>Hello, React!</h1>;
}

export default Greeting;
```

**Creating Class Components**
Class components are ES6 classes that extend the `React.Component` class. They have more features and can manage state.

```jsx
import React, { Component } from 'react';

class Greeting extends Component {
  render() {
    return <h1>Hello, React!</h1>;
  }
}

export default Greeting;
```

**Using Props**
Props (short for "properties") are a way to pass data from a parent component to a child component. They're read-only and help make your components dynamic and customizable.

```jsx
import React from 'react';

function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}

export default Greeting;
```

**Using Components**
To use components, you can simply import and render them within other components.

```jsx
import React from 'react';
import Greeting from './Greeting';

function App() {
  return (
    <div>
      <Greeting name="Alice" />
      <Greeting name="Bob" />
    </div>
  );
}

export default App;
```

**Your Task: Creating a Component Tree**
For this lesson's assignment, create a new React app and define a component tree with at least three levels of components. Pass data using props from parent components to child components and render the data in the UI.

**Conclusion**
Congratulations! You've completed the second lesson in the "Introduction to React.js" course. You now understand the concept of components and how to create both functional and class components. You've also learned about props and how to use them to pass data between components. In the next lesson, we'll dive into state and lifecycle methods in React. Keep up the great work on your journey to mastering React.js!