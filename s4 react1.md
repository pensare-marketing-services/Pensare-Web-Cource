**Introduction to React.js: Lesson 1 - Getting Started with React**

Welcome to the first lesson of the "Introduction to React.js" course! In this lesson, we'll start by introducing you to React.js and guide you through setting up a development environment for creating React applications.

**What is React.js?**
React.js is a JavaScript library developed by Facebook for building user interfaces. It allows you to create reusable components that update efficiently and provide a seamless user experience. React is used to build single-page applications (SPAs) and complex user interfaces for web and mobile applications.

**Setting Up the Development Environment**
Before you start building with React, you need to set up your development environment. Here's a step-by-step guide:

1. **Node.js and npm:** React applications are typically created using Node.js and its package manager npm (Node Package Manager). Download and install Node.js from the official website: [Node.js](https://nodejs.org/).

2. **Create React App:** Facebook provides a tool called Create React App that makes it easy to set up a new React project with a predefined structure and configuration. Open your terminal and run the following command to install Create React App globally:
   
   ```
   npm install -g create-react-app
   ```

3. **Create Your First React App:** Once Create React App is installed, you can create your first React application. In your terminal, navigate to the directory where you want to create the app and run the following command:

   ```
   npx create-react-app my-react-app
   ```

   Replace "my-react-app" with your desired app name.

4. **Navigate to App Directory:** After the app is created, navigate to its directory:

   ```
   cd my-react-app
   ```

5. **Start the Development Server:** Now, start the development server by running the following command:

   ```
   npm start
   ```

   This will start the development server and open your React app in a web browser.

**Creating Your First React Component**
React applications are built using components. Components are the building blocks of a React app. Let's create your first React component:

1. Open the `src` directory in your React app and locate the `App.js` file.
2. Replace the existing code with the following:

```jsx
import React from 'react';

function App() {
  return (
    <div>
      <h1>Hello, React!</h1>
    </div>
  );
}

export default App;
```

3. You'll see that the browser automatically updates with the changes. You've just created and rendered your first React component!

**Your Task: Create a Simple React App**
For this lesson's assignment, follow the steps to create a simple React app. Modify the `App.js` component to display a message of your choice. Observe how changes in the code are reflected in the browser.

**Conclusion**
Congratulations! You've completed the first lesson in the "Introduction to React.js" course. You've been introduced to React.js, set up your development environment, and created your first React component. In the next lesson, we'll dive deeper into components and learn about props. Keep up the great work on your journey to becoming a proficient React developer!