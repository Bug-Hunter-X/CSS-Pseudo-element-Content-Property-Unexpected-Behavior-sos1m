# CSS Pseudo-element Content Property Unexpected Behavior

This repository demonstrates an uncommon CSS bug related to the `content` property used with `::before` and `::after` pseudo-elements.  In certain cases, omitting the `content` property can lead to unpredictable rendering results across different browsers.

The `bug.css` file shows the problematic code.  The `bugSolution.css` file provides a corrected version.

This bug is subtle and might not be immediately apparent, especially if you are not familiar with the default behavior of the `content` property in different browser implementations.