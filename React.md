# React Js
React JS is a JavaScript library for building user interfaces. It is declarative, efficient, and flexible. React makes it easy to create interactive UIs by using a component-based approach.

## History of React js
React was created by Jordan Walke, a software engineer at Meta, who released an early prototype of React called "FaxJS" in 2010. He was inspired by XHP, an HTML component library for PHP.

React was first deployed on Facebook's News Feed in 2011 and later on Instagram in 2012. It was open-sourced at JSConf US in May 2013.

## How to Use React Js
import React from 'react';

function App() {
  const [count, setCount] = React.useState(0);

  function handleClick() {
    setCount(count + 1);
  }

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={handleClick}>Increment</button>
    </div>
  );
}

export default App;

## explanation of the code:
This code defines a simple component called App. This component has a state variable called count, which is initialized to 0. The component also has a function called handleClick(), which increments the count state variable.
The render() function of the App component returns a div element that contains an h1 element and a button element. The h1 element displays the current value of the count state variable. The button element has an onClick event handler that calls the handleClick() function.
When the user clicks the button, the handleClick() function is called, which increments the count state variable. This causes the render() function to be called again, which updates the UI to display the new value of the count state variable.

## Benefits of using React JS:

It is declarative, which makes it easy to create and maintain UIs.
It is efficient, because it uses a virtual DOM to efficiently update the UI.
It is flexible, because it can be used to build a wide variety of UIs.
It has a large and active community, which means that there are many resources available to help you learn and use React JS.



