# Preparing for bootcamp

The following list of questions and concepts can be used to self-assess so you'll know what to work on while preparing for bootcamp.

> In order to get the most learning out of this tool, do not display the answer right away. Think about it, do some searches, and have an opinion _before_ you verify your answer.

## HTML

* What role does HTML play in a web page compared to CSS and JavaScript?
  <details>
    <summary>Verify your answer</summary>

    **HTML provides the structure ... the scaffolding for the page. Like our body's skeletal system.**

  </details>
* What are the syntax parts of an HTML element?
  <details>
    <summary>Verify your answer</summary>

    **The opening tag, the attribute's name and value, the contents of the element, and the closing tag: `<opening name="value">contents</closing>` Some are optional depending on the element.**

  </details>
* What are the HTML elements that make up the basic parts of every web page?
  <details>
    <summary>Verify your answer</summary>

    **`<html>`, `<head>`, and `<body>` If you listed more, cool!**

  </details>
* What are some HTML elements that don't have the closing part?
  <details>
    <summary>Verify your answer</summary>

    **Some of the popular ones are `<img>`, `<input>`, `<br>`, `<hr>`, `<link>`, and `<meta>`, but there are more.**

  </details>
* What element is used to create:
    - Hyperlinks (and what is the one attribute you **must** have?)
      <details>
        <summary>Verify your answer</summary>
        
        **`<a>` and the `href` attribute (e.g. `<a href="/home">Go home</a>`).**

      </details>
    - Images (and what is the one attribute you **must** have?)
      <details>
        <summary>Verify your answer</summary>
        
        **`<img>` and the `src` attribute (e.g. `<img src="/images/logo.png">`).**

      </details>
    - A drop down select form field
      <details>
        <summary>Verify your answer</summary>
        
        **The `<select>` element with an `<option>` element for each option.**

      </details>
    - An input text box form field
      <details>
        <summary>Verify your answer</summary>
        
        **`<input>` If you answered `<input type="text">` that's fine, but `text` is the default value for the `type` attribute so you really don't need it.**

      </details>
    - A button (there are 2 options - do you know both?)
      <details>
        <summary>Verify your answer</summary>
        
        **`<button>`, `<input type="button">` or `<input type="submit">`**

      </details>
* When would you use a radio control versus a checkbox?
  <details>
    <summary>Verify your answer</summary>

    **A radio control is used when the user can only select a single option. A checkbox is used when they can choose more than one option.**

  </details>
* What are the two main types of HTML elements used inside the `<body>` element (specifically related to styling)? What are some of the examples of each?
  <details>
    <summary>Verify your answer</summary>

    **Inline elements such as `<i>` and `<img>`. Block-level elements such as `<div>` and `<p>`.**

  </details>

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

