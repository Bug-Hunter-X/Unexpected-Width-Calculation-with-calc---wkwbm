# Unexpected Width Calculation with calc()

This repository demonstrates a common issue encountered when using the `calc()` function in CSS. The problem arises from misinterpreting how `calc()` interacts with nested elements and percentage-based widths.

**The Bug:**
The `bug.css` file contains a CSS rule that attempts to calculate the width of an inner element based on the width of its parent. However, if the parent's width is less than 100% of its own container, the calculation yields incorrect results. 

**The Solution:**
The `bugSolution.css` file shows a corrected approach.  It clarifies how to ensure that the percentage calculation in `calc()` is relative to the desired container width. This is explained in detail within the CSS comments.