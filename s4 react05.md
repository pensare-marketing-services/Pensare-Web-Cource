**Introduction to React.js: Lesson 5 - Conditional Rendering**

Welcome to the fifth lesson of the "Introduction to React.js" course! In this lesson, we'll explore conditional rendering in React. Conditional rendering allows you to display different content based on certain conditions, making your components more dynamic and responsive.

**Using Conditional Statements**
You can use conditional statements like `if`, `else`, and `ternary operators` in JSX to conditionally render content.

```jsx
import React from 'react';

function Greeting(props) {
  if (props.isLoggedIn) {
    return <p>Welcome back, {props.username}!</p>;
  } else {
    return <p>Please log in.</p>;
  }
}

export default Greeting;
```

```jsx
import React from 'react';

function Discount(props) {
  return props.isPremium ? <p>10% off for premium members</p> : null;
}

export default Discount;
```

**Using Logical && Operator**
The `&&` operator can also be used for conditional rendering. If the expression on the left is truthy, the element on the right will be rendered.

```jsx
import React from 'react';

function Message(props) {
  return <p>{props.isError && 'Error occurred'}</p>;
}

export default Message;
```

**Using the Ternary Operator**
The ternary operator is a concise way to conditionally render content. It's especially useful for simple conditions.

```jsx
import React from 'react';

function Status(props) {
  return <p>Status: {props.isOnline ? 'Online' : 'Offline'}</p>;
}

export default Status;
```

**Your Task: Login Status**
For this lesson's assignment, create a LoginStatus component that displays a message based on whether a user is logged in or not. Use conditional rendering to show different messages for each case.

**Conclusion**
Congratulations! You've completed the fifth lesson in the "Introduction to React.js" course. You've learned how to use conditional rendering to display different content based on conditions in your React components. This dynamic feature enhances the user experience by providing relevant information. In the next lesson, we'll explore rendering lists of items using the map function. Keep up the great work on your journey to mastering React.js!