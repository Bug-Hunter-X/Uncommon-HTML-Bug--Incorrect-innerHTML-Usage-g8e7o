# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug related to the usage of `innerHTML` in HTML. The bug arises from attempting to directly assign an HTML element without proper string concatenation.

## Bug Description
The `innerHTML` property is used to set the HTML content of an element. However, attempting to directly assign an HTML element (like `<p>This is a paragraph.</p>`) will not work as expected. Instead, it should be assigned as a string.

## Bug Solution
The solution involves properly constructing the string representation of the HTML element before assigning it to `innerHTML`. This ensures that the HTML is interpreted and rendered correctly.