# Uncommon HTML Bug: Incorrect DOM Manipulation

This repository demonstrates a common error when manipulating the Document Object Model (DOM) using JavaScript within an HTML file. The bug lies in the incorrect use of the `document.getElementsById` method, which is often mistaken for `document.getElementById`.

## Description
The provided HTML file includes a simple div element. The JavaScript code attempts to hide this div by changing its display style to 'none'.  However, due to the incorrect method used (`getElementsById`), it fails to correctly manipulate the element, leading to unexpected behavior.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe that the text within the div is still visible, indicating the bug.

## Solution
The solution involves changing the JavaScript code to use the correct `document.getElementById` method which returns a single element.