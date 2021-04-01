# Introduction Script

## ACCESS CONTENT
* You can use JavaScript to select any element, attribute, or text from an
HTML page. For example:
1- Select the text inside all of the <hl> elements on a page
2- Select any elements that have a class attribute with a value of note
3- Find out what was entered into a text input whose id attribute has a
value of ema i 1.

## MODIFY CONTENT
You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example:
1. Add a paragraph of text after the first <hl> element
2. Change the value of c 1 ass attributes to trigger new CSS rules
for those elements
3. Change the size or position of an <img> element

## PROGRAM RULES
You can specify a set of steps for the browser to follow (like a recipe )which allows it to access or change the content of a page. For example:
1. A gallery script could check which image a user clicked on and display
a larger version of that image.
2. A mortgage calculator could collect values from a form, perform a calculation, and display repayments.
4. An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport).

## REACT TO EVENTS
You can specify that a script should run when a specific event has occurred. For example, it could be run when:
1. A button is pressed
2. A link is clicked (or tapped) on
3. A cursor hovers over an element
4. Information is added to a form
5. An interval of time has passed
6. A web page has finished loading

## Summary
* A script is a series of instructions that the computer can follow in order to achieve a goal.
* Each time the script runs, it might only use a subset of all the instructions.
* Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
* To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). 

# Expresssions Operators

## RULES FOR NAMING VARIABLES
* The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.

* The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 

* You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used
in a future version of JavaScript.
ONLINE EXTRA
View a full list of keywords and
reserved words in JavaScript. 

* All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two
variables that have the same name using different cases.

* Use a name that describes the kind of information that the variable stores. For example, firstName might be used to store a person's first name, lastNarne for their last name, and age for their age.

* If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.
For example, firstName rather than firstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).

## ARRAYS
* An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

### CREATING AN ARRAY
var colors;
colors ['white', 'black', ' custom'];
var el document.getElementByld('col ors');
el . textContent = col ors[O]; 

### EXPRESSIONS
1. EXPRESSIONS THAT JUST ASSIGN VALUE TO A VARIABLE.
var color = 'beige'; 
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE.
var area = 3 * 2;

### OPERATORS
* Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
Examples:
color = 'beige'; 
area = 3 * 2;
buy = (5 > 3) && (2 < 4);

# WHAT IS A FUNCTION? 
* Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

## A BASIC FUNCTION 
* <img src="Capture.jpg" alt="">

## DECLARING A FUNCTION
* function sayHello() {
    document.write('HELLO!');
}


## BASIC JAVASCRIPT SUMMARY
* A script is made up of a series of statements. Each statement is like a step in a recipe.
* Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
* Variables are used to temporarily store pieces of information used in the script.
* Arrays are special types of variables that store more than one piece of related information.
* JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false). Expressions evaluate into a single value.
* Expressions rely on operators to calculate a value.

