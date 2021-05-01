# reading 04

## Forms:
* Forms are very useful in any web application.
* HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.

> <form>
  <label>
    Name:
    <input type="text" name="name" />
  </label>
  <input type="submit" value="Submit" />
 </form>
  
* There are two types of form input in React. We have the uncontrolled input and the controlled input. 

* The controlled input is when the React component that renders a form also controls what happens in that form on subsequent user input. 

* TextInput Component: There are different input elements, e.g., text, email, password, select option, checkbox, date, and radio button. 

* The textarea Tag: In HTML, a `<textarea>` element defines its text by its children.

The select Tag: In HTML, `<select>` creates a drop-down list. For example, this HTML creates a drop-down list of flavors.

* Handling Multiple Form Inputs: In most situations, we are going to have more than one form input. 

* form validation out of the box, you have to handle forms yourself in React. This brings about many complications, like how to get form values, how to manage form state, and how to validate a form on the fly and show validation messages.

## The Conditional (Ternary) Operator Explained:

* Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.

* The Conditional (Ternary) Operator
> if ( condition ) {
  value if true;
} else {
  value if false;
}

- Now, the ternary operator:
> condition ? value if true : value if false

* We can nest ternary operators to test multiple conditions.

#### Example:
>   let isStudent = false;
    let isSenior = true;let price = isStudent ? 8 : isSenior ? 6 : 10
    console.log(price);

* Multiple operations: It is also possible to run multiple operations within a ternary.

#### Example:
> let isStudent = true;
let price = 12;isStudent ? (
  price = 8,
  alert('Please check for student ID')
) : (
  alert('Enjoy the movie')
);



