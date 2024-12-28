This repository demonstrates an uncommon bug in HTML involving the use of innerHTML.  The bug occurs when a non-string value (in this case, a number) is assigned to the innerHTML property of an element. This causes a runtime error in most browsers.

The `bug.html` file shows the buggy code. The `bugSolution.html` file demonstrates the corrected code, which converts the numeric value to a string before setting the innerHTML property.