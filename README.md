# CSS `calc()` function unexpected behavior
This repository demonstrates a common issue encountered when using the CSS `calc()` function: unexpected behavior due to inconsistent units or complex calculations. The `bug.css` file contains the problematic CSS, while `bugSolution.css` shows the corrected version.  The issue primarily stems from mixing percentage and pixel values within the calculation without proper consideration of context.  Refer to the code for a clear example. 

## How to reproduce:
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected width of the element.
4. Compare it to the expected width in `bugSolution.html`.

## Solution:
Ensure that units are consistent within the `calc()` function, and break down complex calculations into simpler steps for better readability and predictability.