# CSS `calc()` Function Error with Negative Values

This repository demonstrates a subtle bug related to the CSS `calc()` function.  The bug arises when the calculation within `calc()` results in a negative value.  The browser's handling of such negative values can be inconsistent and lead to unexpected visual rendering issues.

**Bug:** Using `calc()` with percentages and other units, if the calculation produces a negative number, the result may not be handled correctly, causing elements to disappear or be positioned incorrectly.

**Solution:** Add safeguards to the calculation to prevent negative results or handle negative values gracefully.
