# Typo in getElementById

This example demonstrates a simple yet easily overlooked error in HTML/JavaScript: a typo in the `getElementById` method.

The `bug.html` file contains a script attempting to change the text content of an element with the ID "myDiv". However, due to a typo (`getElementByIdx` instead of `getElementById`), the script fails silently and the text remains unchanged.

The `bugSolution.html` file shows the corrected code.