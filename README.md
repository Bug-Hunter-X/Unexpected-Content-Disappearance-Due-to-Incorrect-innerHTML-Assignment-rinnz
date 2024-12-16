# Uncommon HTML Bug: Unexpected Content Disappearance

This repository demonstrates an uncommon bug in HTML where setting the `innerHTML` property of an element to `null` unexpectedly removes the content.  This can be problematic as it's not immediately obvious why the content disappears.

## Bug Description
The bug involves using JavaScript to manipulate the content of an HTML element.  When `innerHTML` is set to `null`, the content is completely removed, leading to an unexpected empty element.

## Solution
The solution involves using an empty string (`""`) instead of `null` when clearing the content of an HTML element, ensuring that the element remains intact while its content is removed.