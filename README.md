# CSS Background Image Loading Error

This repository demonstrates a common CSS error related to the `url()` function used for setting background images.  A simple typo in the URL path prevents the image from loading correctly. The solution provides the correct syntax.

## Bug

The `bug.css` file contains an incorrectly formatted `url()` function.  This results in the background image not being displayed.

## Solution

The `bugSolution.css` file demonstrates the corrected syntax, using double quotes around the image path to resolve the issue.

## How to reproduce

1. Clone this repository.
2. Create a file named `my-image.jpg` in the same directory as the CSS files.
3. Include `bug.css` in an HTML file. You'll observe that the background image doesn't appear.
4. Replace `bug.css` with `bugSolution.css`.  The background image should now display correctly.