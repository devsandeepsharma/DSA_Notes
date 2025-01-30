# Input and Output in JavaScript

In JavaScript, input and output are easier compared to other programming languages.

## Output in JavaScript

We will use output statements a lot in DSA for debugging and printing results. The most common way to display output is using console.log().

```javascript
    console.log("Hello, World!");
```

## Input in JavaScript

In DSA, taking input from the user is less common because problems usually come with predefined input. However, if needed, we can use prompt().

```javascript
    prompt("Enter your input:");
``
(Note: prompt() only works in the browser, not in Node.js.)

For Node.js, we use:

```javascript
const readline = require("readline-sync");
let input = readline.question("Enter input: ");
console.log("You entered:", input);
```