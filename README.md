# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  The `bug.css` file contains CSS code with conflicting selectors, leading to unexpected styling. The `bugSolution.css` file shows how to resolve the issue.

## Bug Description

The bug stems from a conflict between selectors with different specificity levels. A more specific selector unintentionally overrides a more general one, resulting in an unexpected visual appearance.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the unexpected styling of an element due to specificity issues.

## Solution

The `bugSolution.css` file provides a solution by adjusting selectors and/or using the `!important` flag cautiously(use it sparingly).