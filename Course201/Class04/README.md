# CSS Layout
Normal flow - or the way the webpage elements lay themselves out if you haven't changed their layout.

Block elements start from a new line.
inline elements never start from a new line
block elements cover space as far as it can go either directons
inline elements only covers the space as bounded by the tags in the HTML elememt.

Some key advantages include less dependency on margining or floating
Absolute positioning is that it allows developers to precisely control the position of elements on a web page. This can be useful for creating complex, multi-layered layouts, and for positioning elements in specific locations on the page.
which can make it easier to create complex layouts and avoid conflicts with other elements on the page.

fixed; property applied to an element will cause it to always stay in the same place even if the page is scrolled. To position the element we use top, right, bottom, left properties.

While a  absolute; will cause it to adjust its position with respect to its parent. If no parent is present, then it uses the document body as parent.

# Functions - reusable blocks of Code

Difference between a function declaration and a function invocation:
A function declaration is a way to define a function in JavaScript, using the function keyword followed by the function name, and the function's code block enclosed in curly braces. For example:

function greet(name) {
  console.log(`Hello, ${name}!`);
}

A function invocation, on the other hand, is a way to call a function that has been defined elsewhere in the code. It involves using the function name followed by parentheses, which may contain arguments (values passed to the function). For example:

greet("John"); // Outputs: "Hello, John!"

Difference between a parameter and an argument:
In JavaScript (and other programming languages), a parameter is a variable declared in the function's declaration, which represents a value that the function expects to receive as input. Parameters are used to define the function's behavior and can be named anything you like. For example, in the greet function declaration above, name is the parameter.

An argument, on the other hand, is a value passed to a function when it is invoked, which corresponds to a parameter. Arguments are used to provide input to the function and can be any value or expression that evaluates to a value. For example, in the greet function invocation above, "John" is the argument passed to the function, which corresponds to the name parameter.

In summary, parameters are declared in the function definition and serve as placeholders for values that the function expects to receive as input, while arguments are values passed to the function when it is called, which correspond to the function's parameters.