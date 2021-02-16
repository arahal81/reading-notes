# read 9

## Forms
* There are several types of form controls that you can use to collect information from visitors to your site.
 * ADDING TEXT Text input, Password input and Text area 
 * Making Choices: Radio buttons, Checkboxes, Drop-down boxes
 * Submitting Forms: Submit buttons, Image buttons
 * Uploading Files: Allows users to upload files to a website.
 #### How Forms Work A user fills in a form and then presses a button to submit the information to the server.
 * Form controls live inside a `<form>` element.
 * Every `<form>` element requires an action attribute.
 * Forms can be sent using one of two methods: get or post.
 * `<Label>` When introducing form controls, the code was kept simple by indicating the purpose of each one in text next to it.
 * You can group related form controls together inside the `<fieldset>` element.
 * The `<legend>` element can come directly after the opening `<fieldset>` tag and contains a caption which helps identify the purpose of that group of form controls.
 * you can use an `<input>` element and give the type attribute a value of date.

## Lists, Tables And Forms
* In addition to the CSS p XX roperties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
* List markers can be given different appearances using the list-style-type and list-style image properties.
* Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
* Forms are easier to use if the form controls are vertically aligned using CSS.
* Forms benefit from styles that make them feel more interactive.

## Events 
* Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
* Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
* When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
You can use event delegation to monitor for events
that happen on all of the children of an element. 
* The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.