# reading 03


## Lifting State Up:

* by Lifting up the state we make the state of the parent component as a single source of truth and pass the data of the parent in its children.

* the data can be stored in the state by the Parent Component and we also meet other important principle that There should be a single “source of truth” for any data that changes in a React application.

* Lifting state involves writing more “boilerplate” code than two-way binding approaches, but as a benefit, it takes less work to find and isolate bugs. 



## Lists and Keys:

* A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted.

*  In other words, we can say that keys are used to give an identity to the elements in the lists. 

* You can also assign the array indexes as keys to the list items.


## How to Use the Spread Operator (…) in JavaScript

* Spread operator allows an iterable to expand in places where arguments are expected.

* used in the variable array where there is more than one values are expected.

*  It allows us the privilege to obtain a list of parameters from an array. 