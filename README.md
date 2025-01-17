This repository demonstrates a subtle bug in CSS Flexbox layout.  The issue arises when using `justify-content: space-between` with child elements that have a fixed width and content that might overflow. The fixed width overrides the space-between distribution, leading to unexpected stacking or overlapping of elements.

The `bug.css` file shows the problematic CSS. `bugSolution.css` provides a solution to fix the layout issue.