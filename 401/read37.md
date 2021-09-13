# Reading 37

## JSX

JSX is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

## Why JSX?

React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

### JSX is an Expression Too

After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.

This means that you can use JSX inside of if statements and for loops, assign it to variables, accept it as arguments, and return it from functions.

## React 1

React is a JavaScript library, and so we’ll assume you have a basic understanding of the JavaScript language. If you don’t feel very confident, we recommend going through a JavaScript tutorial to check your knowledge level and enable you to follow along this guide without getting lost.

### Components and Props

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.

Function and Class Components
The simplest way to define a component is to write a JavaScript function:

`function Welcome(props) { return <h1>Hello, {props.name}</h1>; }`

This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.

## State and Lifecycle

In applications with many components, it’s very important to free up resources taken by the components when they are destroyed.
There are three things you should know about setState() which are:

    - Do Not Modify State Directly
    - State Updates May Be Asynchronous
    - State Updates are Merged

### Handling Events

Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences: - React events are named using camelCase, rather than lowercase. - With JSX you pass a function as the event handler, rather than a string.
