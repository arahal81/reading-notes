# Read 2

## Text

#### HTML elements are used to describe the structure of the page
* **Structural markup:** the elements that you can use to describe both headings and paragraphs.
    * **Headings** ```<h1>...<h6>``` is levels" of headings ```<h1>```element is the largest size and ```<h6>``` element is the smallest size.
    * **Paragraphs** ```<p>``` To create a paragraph, surround the words that make up the paragraph with an opening ``` <p>``` tag and closing ```</p>``` tag.
    * **Bold** By enclosing words in the tags ```<b>``` and ```</b>``` we can make characters appear bold.
    * *Italic* By enclosing words in the tags ```<i>``` and ```</i>``` we can make characters appear italic.
    * **Superscript** The ```<sup>``` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power.
    * **Subscript** The ```<sub>``` element is used to contain characters that should be subscript.
    * **Line Breaks** As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag ```<br />```.
    * **Horizontal Rules** To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the ```<hr />``` tag.
* **Semantic Markup** There are some text elements that are not intended to affect the structure of your web pages, but they do add     extra information to the pages — they are known as semantic markup.
    * **Strong** The use of the ```<strong>``` element indicates that its content has strong importance.
    * **Emphasis** The ```<em>``` element indicates emphasis that subtly changes the meaning of a sentence.
    * **Quotations** The ```<blockquote>``` element is used for longer quotes that take up an entire paragraph, The ```<q>``` element is used for shorter quotes that sit within a paragraph.
    * **Abbreviations** If you use an abbreviation or an acronym, then the ```<abbr>``` element can be used.
    * **Citations** When you are referencing a piece of work such as a book, film or research paper, the ```<cite>``` element can be used to indicate where the citation is from.
    * **Definitions** The ```<dfn>``` element is used to indicate the defining instance of a new term.
    * **Author Details** The ```<address>``` element has quite a specific use: to contain contact details for the author of the page.
## Introducing CSS
**CSS treats each HTML e XX lement as if it appears inside its own box and uses rules to indicate how that element should look.**
* CSS Associates Style rules with HTML elements. css rule contains two parts: a selector and a declaration. ```p {font-family: Arial;}```
* CSS Properties Affect How Elements Are Displayed,CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value
#### CSS Selectors:
* Universal Selector ```* {}```
* Type Selector ```h1, h2, h3 {}```
* Cl ass Selector ```.note {}```
* ID Selector ```#introduction {}```
* Child Selector ```li>a {}```

## Basic JavaScript Instructions
* **STATEMENTS**A script is a series of instructions that a computer can follow one-by-one.  
* **COMMENTS** You should write comments to explain what your code does, They help make your code easier to read and understand.
* **VARIABLE** A script will have to temporarily store the bits of information it needs to do its job.```var varName;```
* **DATA TYPES** JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.
* **ARRAYS** is a special type of variable. It doesn't just store one value; it stores a list of values.
* **VALUES IN ARRAYS** Values in an array are accessed as if they are in a numbered list, the numbering of this list starts at zero (not one).
* **EXPRESSIONS** An expression evaluates into (results in) a single value
* **OPERATORS** allow programmers to create a single value from one or more values.
    * ASSIGNMENT OPERATORS ``` = ```
    * COMPARISON OPERATORS ``` <,>,<=,>=,==,===,!=``` 
    * ARITHMETIC OPERATORS ``` +,-,*,--,++,/,% ```
## Decisions and Loops
#### the result of evaluating conditions will be boolean "true or false"
* is equal to ```==```.
* is not equal to ```!=```.
* strict equal to ```===```.
* strict not equal to ```!==```.
* greater than ```>```.
* less than ```<```.
* greater than or equal to ```>=```.
* less than or equalto ```<=```.
#### Logical Operators 
* logical and ```&&```.
* logical or ```||```.
* logical not ```!```.
#### IF STATEMANTS: The if statemant evaluates and checks a condition
  ``` if(condition ){if true} else {if false} ```
#### SWITCH STATEMENTS
**A switch statement starts with a variable called the switch value, Each case indicates a possible value for this variable and the code that should run if the variable matches that value.**
    ``` switch (level) {```
    ``` case 'O ne ':```
    ``` title= 'Level 1 ' ;```
    ``` break;```
    ``` case 'Two':```
    ``` tit 1 e = ' Level 2 ' ;```
    ``` break;```
    ``` case ' Three' :```
    ``` title = 'Level 3' ;```
    ``` break ;```
    ```  default :```
    ```  title= 'Test';```
    ```  break;```
   ``` }```