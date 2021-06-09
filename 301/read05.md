# reading 05

## Thinking in React:

* One of the many great parts of React is how it makes you think about apps as you build them. In this document, 
we’ll walk you through the thought process of building a searchable product data table using React.

### 1: Break The UI Into A Component Hierarchy:

* The one thing about React that often hits non-React developers is the need to drill down your UI into components. 
It is a process of abstracting your UI into little lego-like parts.

### 2: Build A Static Version in React:

* When building your UI, it can be tempting to code each individual component as separate parts and put them all together.
 This can be a logistic issue, especially on the CSS front, when it comes to getting things to sit in the right places for different view ratios.

### 3: Identify The Minimal (but complete) Representation Of UI State:

* This concept is an idea that's not often talked about when we learn React.
 What most of us encounter is that we need to represent our UI state in some form. There is no emphasis on a minimum representation.

### 4: Identify Where Your State Should Live:

*  React is all about one-way data flow down the component hierarchy. 
It may not be immediately clear which component should own what state. 
This is often the most challenging part for newcomers to understand

### 5: Add Inverse Data Flow:

* React uses one-way data flow down the hierarchy.
 This means that children can only consume the data and are unable to enact any changes.