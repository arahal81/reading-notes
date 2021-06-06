# Reading01

## What is React?
* It is a JavaScript library for building user interfaces. Through it we can build complex user interfaces by using small pieces of code called "components".



## What is JSX?
* JSX stands for JavaScript XML.
* JSX is a syntax extension to JavaScript. It is used with React to describe what the user interface should look like. By using JSX.
### Why JSX?
* Instead of separating the markup and logic in separated files, React uses components for this purpose. We will learn about components in detail in further articles.


## Rendering Elements: 
In order to render any element into the Browser DOM, we need to have a container or root DOM element. It is almost a convention to have a div element with the id=”root” to be used as the root DOM element. 

`<div id="root"></div>`

To render a React element into a root DOM node, pass both to ReactDOM.render():

> `const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));`

## React Components and Props:
* Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and  return HTML via a render() function.

* Components come in two types, Class components and Function components.
    * Function components: is just a plain JavaScript function that accepts props as an argument and returns a React element.
    * class component: class component requires you to extend from React. Component and create a render function which returns a React element.

* Another way of handling component properties is by using props.

* Props are like function arguments, and you send them into the component as attributes.
