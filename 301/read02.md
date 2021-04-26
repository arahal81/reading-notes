# reading-02


## State

* State is used with React Component Classes to make them dynamic. It enables the component to keep track of changing information in between renders.

## Lifecycle

* we might define a lifecycle as birth, growth & death. And our React components follow this cycle as well

## A component’s lifecycle can be broken down into four parts:
* Initialization
* Mounting
* Updating
* Unmounting
## Handling events
* React events are named using camelCase, rather than lowercase.
* With JSX you pass a function as the event handler, rather than a string.
* SyntheticEvent wraps round the native event of all browsers, it has the same interface as the browser’s native event. It’s just there to ensure your events work identically across all browsers.
* Calling `bind` in your `render()` method has performance implications as the function you are binding will be reallocated on every render. Bottom line is, if you’re concerned about performance, don’t do it.
* Using arrow functions and `.bind()` methods in JSX Is not a good idea because the function gets recreated on each render and that will hurt performance.

## Conditional Rendering

### In react, you could build recognizable components encapsulating the behavior you need.

* Element variables conditional rendering: You can use variables to store elements. This can help you conditionally render a part of the component while the rest of the output doesn’t change.
* Inline If with Logical && Operator: You may embed expressions in JSX by wrapping them in curly braces. This includes the JavaScript logical && operator.