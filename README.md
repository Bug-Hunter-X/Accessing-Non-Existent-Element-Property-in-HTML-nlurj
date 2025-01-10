# Accessing Non-Existent Element Property in HTML

This repository demonstrates an uncommon error in HTML: attempting to access a property of an element that does not exist or does not have that specific property. This can lead to unexpected behavior or silent failures, making it harder to debug.

## The Bug

The `bug.html` file contains a script that attempts to set a non-existent property (`nonExistentProperty`) on an element (`myDiv`).  Modern browsers might not throw an error, but the action has no effect.

## The Solution

The `solution.html` file provides a corrected version.  It includes checks to ensure the element exists before attempting to access or modify its properties, using a conditional statement to handle the case where the element is not found.