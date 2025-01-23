# Missing Quotes in document.getElementById()

This repository demonstrates a common yet easily overlooked error in JavaScript when interacting with HTML elements using `document.getElementById()`. The error arises from forgetting to enclose the ID in quotes when attempting to access an element.

## Bug

The `bug.html` file contains a script that attempts to modify the innerHTML of a div with id "myDiv". However, the script incorrectly omits quotes around 'myDiv', leading to a runtime error.

## Solution

The `bugSolution.html` file corrects this by properly encapsulating the ID within quotes, ensuring the script correctly identifies and modifies the intended element.