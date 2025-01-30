# Variables 📦📦

Variables are like containers or boxes where we can store values.

<img src="../assets/variable.png" alt="variable visualization">

## Types of variable declarations

In JavaScript, there are three types of variable declarations:

* 1. var
    * var was the only way to declare variables before ES6.
    * It does not have block scope, which can lead to unexpected errors.
    * It allows re-declaration and re-assignment.
    * Not recommended for modern JavaScript.

    Example:

    ```javascript
    var name = "John";
    var name = "Doe"; // Allowed (Re-declaration)
    name = "Smith";   // Allowed (Re-assignment)
    ```

* 2. let
    * let is block-scoped (only accessible inside the block where it's declared).
    * It allows re-assignment but not re-declaration within the same scope.
    * Preferred over var.

    Example:

    ```javascript
    let age = 25;
    age = 30; // Allowed (Re-assignment)
    let age = 35; // ❌ Error (Cannot re-declare in the same scope)
    ```

* 3. const
    * const is block-scoped, like let.
    * It cannot be re-assigned after declaration.
    * Used for values that should not change (constants).

    Example:

    ```javascript
    const PI = 3.14;
    PI = 3.14159; // ❌ Error (Cannot re-assign)
    ```