# CSS calc() Issue in Nested Elements

This repository demonstrates an issue with the CSS `calc()` function when used with percentages in nested elements. The child element's width calculation is not relative to its parent, as expected, but to the viewport.  This happens even with calculations involving subtractions.

## Steps to Reproduce
1. Clone the repository.
2. Open `index.html` in your browser.
3. Observe that the inner element's width is incorrect; it does not respect the parent's width.

## Solution
The solution involves using absolute units for the child element or relative units consistent with the parent element's structure.  The provided solution file shows how to achieve the desired layout.