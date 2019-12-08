### React Presentation
Hello! My name is Ekaterina.  I’ll tell about one of the JavaScript libraries.
JavaScript libraries are collections of pre-written JS code that can be used for common JS tasks, allowing you to bypass the time intensive process of coding by hand. 
There are a lot of different JS libraries and React JS is one of them.
#### What is React?
React is a JS library for building user interfaces or UIs. In terms of websites and web applications, UIs are the collection of on-screen menus, search bars, buttons, and anything else someone interacts with to use a website or app.
React was created Facebook engineer Jordan Walke in 2011 specifically to improve UI development.
Let’s look at the React in more details.
#### React component
The main concept of React is component.
To write React apps we write React components that correspond to various interface elements. We then organize these components inside higher-level components which define the structure of our application.
The two primary ways of declaring components in React are via functional and class-based components.
Functional components are declared with a function.
This example creates a React component named `Welcome`: 
Component is rendered with the `ReactDOM.render()` method, React applications are usually built around a single HTML element, called root node.
React can also use ES6 classes to create components.
We create a component by extending upon the React-Component class. Inside `render()` we will return a description of what we want React to draw on the page.
#### What is JSX used for in React?
JSX stands for JavaScript XML.
JSX allows to write HTML elements in React and add them in the DOM without any `createElement()` and `appendChild()` methods.
Look at two examples, the first uses JSX and the second does not.
We are not required to use JSX, but JSX makes it easier to write React applications.
With JSX you can write expressions inside curly braces `{ }`.
The expression can be a React variable, or property, or any other valid JavaScript expression. JSX will execute the expression and return the result.
#### React Props
Short for properties, Props are arguments passed into React components via HTML attributes.
This example creates a React component named `Welcome` with property:
1.	We call `ReactDOM.render()` with the `Welcome` element.
2.	React calls the `Welcome` component with `{name: 'React'}` as the props.
3.	Our `Welcome` component returns a `<h1>` element as the result.

Props also pass data from one component to another as parameters.
In this example we send `brand` property from the `Garage` component to the `Car` component.
Props should not be modified inside the component.
#### React state
React components has a built-in state object, where store property values that belongs to the component.
The state object is initialized in the constructor and can contain properties.
Сan refer to the state object anywhere in the component by using the `this.state.propertyname` syntax.
To change a value in the state object, use the `this.setState()` method.
When a value in the state object changes, the component will re-render.
#### Virtual DOM
React JS creates a Virtual DOM, a copy of the site’s DOM. React JS uses the Virtual DOM to see what parts of the actual DOM need to change when an event happens and selective updates that section of the DOM only. This kind updating takes less computing power and less loading time. 

I hope you got a brief idea of React library. Thanks for watching!