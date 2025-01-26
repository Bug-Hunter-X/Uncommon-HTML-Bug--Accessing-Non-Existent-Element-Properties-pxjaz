# Uncommon HTML Bug: Accessing Non-Existent Element Properties

This repository demonstrates a subtle but potentially problematic error in JavaScript code interacting with the HTML DOM. The bug occurs when attempting to access properties of an element that does not exist in the HTML structure. 

## The Bug

The `bug.html` file contains a script that tries to access the `textContent` property of an element (`myNonExistentDiv`) that is not present in the HTML. This will not throw an error, but could lead to unexpected behavior or logical errors.  The solution demonstrates robust error handling.

## The Solution

The `bugSolution.html` file corrects this by explicitly checking if the element exists before attempting to access its properties.