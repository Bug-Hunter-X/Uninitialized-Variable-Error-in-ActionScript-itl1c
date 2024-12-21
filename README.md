# Uninitialized Variable Bug in ActionScript

This repository demonstrates a common runtime error in ActionScript 3: accessing an uninitialized variable.  The `bug.as` file shows the erroneous code, while `bugSolution.as` provides a corrected version.

The bug arises from attempting to use a variable (`x` in this case) before assigning it a value. This leads to a runtime error, often difficult to track down without careful debugging.

**Solution:** Always initialize variables before using them, even if the initialization is to a default value.