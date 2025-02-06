# Unexpected Behavior with CSS calc() function

This repository demonstrates some uncommon issues that can arise when using the `calc()` function in CSS.  Specifically, we'll look at problems related to unit inconsistencies and operator precedence.

## Bug.css

The `bug.css` file contains examples showcasing these problems.  You'll observe unexpected results in the layout due to the incorrect usage of `calc()`.

## BugSolution.css

The `bugSolution.css` file provides corrected versions of the CSS, demonstrating how to properly use the `calc()` function and avoid the issues presented in `bug.css`.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser.  Observe the unexpected layout behavior.
3. Replace `bug.css` with `bugSolution.css`. Observe the corrected layout.

This example helps illustrate the importance of paying close attention to units and operator precedence when using the powerful `calc()` function in CSS.