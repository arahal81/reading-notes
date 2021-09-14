# Reading 38

## React II

Conditional Rendering
Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them. Consider two components

### Element Variables

You can use variables to store elements. This can help you conditionally render a part of the component while the rest of the output doesn’t change.

It works because in JavaScript, true && expression always evaluates to expression, and false && expression always evaluates to false.

Therefore, if the condition is true, the element right after && will appear in the output. If it is false, React will ignore and skip it.

### Inline If-Else with Conditional Operator

Another method for conditionally rendering elements inline is to use the JavaScript conditional operator condition ? true : false.

Just like in JavaScript, it is up to you to choose an appropriate style based on what you and your team consider more readable. Also remember that whenever conditions become too complex, it might be a good time to extract a component.

Preventing Component from Rendering In rare cases you might want a component to hide itself even though it was rendered by another component. To do this return null instead of its render output.

## Lists & Keys

Given the code below, we use the map() function to take an array of numbers and double their values. We assign the new array returned by map() to the variable doubled and log it:

const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map((number) => number \* 2);
console.log(doubled);
This code logs [2, 4, 6, 8, 10] to the console.

In React, transforming arrays into lists of elements is nearly identical.

## Rendering Multiple Components

You can build collections of elements and include them in JSX using curly braces {}.

### Keys

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

The best way to pick a key is to use a string that uniquely identifies a list item among its siblings.

We don’t recommend using indexes for keys if the order of items may change. This can negatively impact performance and may cause issues with component state. Check out Robin Pokorny’s article for an in-depth explanation on the negative impacts of using an index as a key. If you choose not to assign an explicit key to list items then React will default to using indexes as keys.

Here is an in-depth explanation about why keys are necessary if you’re interested in learning more.

Extracting Components with Keys
Keys only make sense in the context of the surrounding array.

For example, if you extract a ListItem component, you should keep the key on the `<ListItem />` elements in the array rather than on the `<li>` element in the ListItem itself.

## Forms

HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

Controlled Components In HTML, form elements such as , `<textarea>`, and typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components,
and only updated with setState(). The textarea Tag In React, a `<textarea>` uses a value attribute instead. This way, a form using a `<textarea>` can be written very similarly to a form that uses a single-line input The select Tag React, instead of using this selected attribute, uses a value attribute on the root select tag. This is more convenient in a controlled component because we only need to update it in one place. To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.
To make UI interactive, you need to be able to trigger changes to the underlying data model. React achieves this with state. Lists and Keys In React, transforming arrays into lists of elements is nearly identical. Rendering Multiple Components we can build collections of elements and include them in JSX using curly braces {} One of the many great parts of React is how it makes you think about apps as you build them. In this document, we’ll walk you through the thought process of building a searchable product data table using React. To build the app correctly, you first need to think of the minimal set of mutable state that your app needs. The key here is DRY: Don’t Repeat Yourself. Figure out the absolute minimal representation of the state the application needs and compute everything else you need on-demand. For example, if you’re building a TODO list, keep an array of the TODO items around; don’t keep a separate state variable for the count. Instead, when you want to render the TODO count, take the length of the TODO items array.

## Controlled Components

In HTML, form elements such as , `<textarea>`, and typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(). We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
