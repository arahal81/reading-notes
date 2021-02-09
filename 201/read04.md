# read 5

## LINKS
#### Links are the defining feature of the web because they allow you to move from one web page to another
* Links are created using the ```<a>``` element which has an attribute called href. ```<a href="http://www.google.com">google</a>```
* Relative URLs Relative URLs can be used when linking to pages within your own website.
    * Same Folder ```<a href="fileName.html">url_text</a>```
    * **Child Folder ```<a href="folder/fileName.html">url_text</a>``` Functions let you group a series of statements together to perf
    * To create function " function function_Name() {the statements that perform the task} ".
* To call a function " function_Name(); ".
* To create function taking parameters " function function_Name(parameter1,parameter2...) {the statements that perform the task} ".
* To call a function taking parameters "function_Name(value1, value2......); "
* To getting a singel value out of a function " 
    function function_Name(parameter1,parameter2 ) 
    {
        var sum = parameter1+parameter2;
        return sum;

    }  "orm a specific task.** 
    * Grandchild Folder ```<a href="root/folder/fileName.html">url_text</a>```
    * Parent Folder ```<a href=".../fileName.html">url_text</a>```
    * GrandParent Folder ```<a href="../../fileName.html">url_text</a>```
* target If you want a link to open in a new window, you can use the target attribute on the opening ```<a>``` tag. The value of this attribute should be _blank. ```<a href="http://www.google.com" target="_blank">```
* Linking to a Specific Part of the Same Page ```<a href="#Part_Name">Part_Name</a>```
## LAYOUT
**Key Concepts in Positioning Elements**
*  Normal Flow ```position:static``` each block-level element sits on top of the next one.
* Relative Positioning ```position:relative```  Relative positioning moves an element in relation to where it would have been in normal flow.
* Absolute Positioning ```position:absolute``` When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.
* Fixed Positioning ```position:fixed``` Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.
* Overlapping Elements ```z-index``` When you use relative, fixed, or absolute positioning, boxes can overlap.
* Floating Elements ```float``` The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
* Clearing Floats ```clear``` The clear property allows you to say that no element (within the same containing element)  
* Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.
* Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window.
* The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.
* CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on.

## Functions
 **Functions let you group a series of statements together to perform a specific task.** 
 * To create function ``` function function_Name() {the statements that perform the task} ```.
* To call a function ``` function_Name(); ```.
* To create function taking parameters ``` function function_Name(parameter1,parameter2...) {the statements that perform the task} ```.
* To call a function taking parameters ```function_Name(value1, value2......); ```
* To getting a singel value out of a function ``` function function_Name(parameter1,parameter2 ) {var sum = parameter1+parameter2 return sum;} ```
* VARIABLE SCOPE The location where you declare a variable will affect where it can be used within your code. 