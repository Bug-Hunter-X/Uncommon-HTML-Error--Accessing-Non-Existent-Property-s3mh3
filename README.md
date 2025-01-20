# Uncommon HTML Bug: Accessing Non-Existent Property

This repository demonstrates a subtle error that can occur in HTML when accessing properties of HTML elements that do not exist.

## The Bug

The `bug.html` file contains a script that attempts to access the `doesNotExist` property of the `myDiv` element.  Since this property doesn't exist, a runtime error occurs.  This can be hard to catch without careful debugging, especially in larger projects.

## The Solution

The `bugSolution.html` file demonstrates the correct way to access properties of an element, using a check to ensure the property exists before accessing it. This prevents runtime errors and makes the code more robust.