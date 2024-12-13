# CSS Specificity Issue: !important and Inheritance

This repository demonstrates a subtle issue related to CSS specificity, the `!important` flag, and inheritance.  The problem arises when trying to override a style set with `!important` using a more specific selector.

## Problem

The `bug.css` file contains CSS that exhibits unexpected behavior due to the interaction of `!important` and selector specificity.  Understanding this interaction is crucial for writing maintainable and predictable CSS.

## Solution

The `bugSolution.css` file provides a corrected approach that avoids the unexpected behavior by carefully managing CSS specificity and minimizing the use of `!important`.

## How to reproduce

1. Clone this repository.
2. Open `bug.html` (or create a simple HTML file and link to `bug.css`) in your web browser.
3. Observe the unexpected styling.
4. Switch to `bugSolution.css` to see the corrected styling.

This example highlights a common pitfall in CSS and reinforces best practices for writing clean and maintainable styles.