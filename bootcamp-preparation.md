# Preparing for bootcamp

The following list of questions and concepts can be used to self-assess so you'll know what to work on while preparing for bootcamp.

## HTML

* What role does HTML play in a web page compared to CSS and JavaScript?
* What are the syntax parts of an HTML element?
* What are some HTML elements that don't have the closing part?
* What are the HTML elements that make up the basic parts of every web page?
* What element is used to create:
  - hyperlinks (and what is the one attribute you MUST have?)
  - images (and what is the one attribute you MUST have?)
  - a drop down select form field
  - an input text box form field
* What are the two main types of HTML elements used inside the `<body>` element (specifically related to styling)?

## CSS

* What role does CSS play in a web page compared to HTML and JavaScript?
* What are the 3 different ways you can apply styles to a web page?
* How would you describe the 'box model'?
* What is meant by 'cascading' styles in CSS?
* What is the most common way to apply styles to one or more elements?

## JavaScript

### Variables

* How do you create a new variable?
* How do you change the value of an existing variable?
* What is the difference between `var`, `let` and `const`? And when should you use them?
* What are the different data types the value of a variable can be?

### Functions

* What is the difference between defining a function and calling a function?
* How do you specify the input parameters of a function?
* How do you specify what the function will return?
* What is the relationship between `name` and `fullName` below:

  ```js
  function showName (name) {
    console.info(name)
  }

  const fullName = 'Mahāttmā Mohandas Karamchand Ghandi'
  showName(fullName)
  ```
* In the following code snippet, which variable(s) are available to `console.log` on line 8?

  ```js
  1  var foo = 1
  2  const bar = 'yo!'
  3  function setup (config) {
  4    const cfg = config
  5    var baz = {}
  6    let bin = 56
  7  }
  8  console.log()
  ```

### Objects

> Note: the terms `property` and `key` are synonymous

* How do you create an object?
* What are 2 ways/syntaxes to get the value of a property on an object?
* How do you add a property to an object?
* When do you **have** to use bracket notation?

### Arrays

* How do you create an array?
* How do you add an item to an array?
* How do you reference a single item in an array given its index?
* What values can you store in an array?

### Conditionals

* What are the possible values that are 'falsy'?
* What are the possible values that are 'truthy'?
* What are the 2 main ways to write conditions? (hint: `if` is one of them)
* What are the 'and' and 'or' boolean operators?
* What are the common comparison operators?
* What is the difference between `==` and `===`?

### Iteration (loops)

* What are some of the common ways to loop over an array?

