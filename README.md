# Uncommon HTML Bug: Self-Appending innerHTML

This repository demonstrates a subtle bug related to directly modifying the innerHTML property of an element by appending it to itself. While generally not a common mistake, it can lead to issues in complex scenarios or with poorly structured code.

## Bug Description:
The `bug.html` file contains code that attempts to add text to a div's innerHTML by appending the existing innerHTML to itself.  While this *seems* to work in this simple example, it's an inefficient and potentially problematic approach, particularly in more complex scenarios.

## Solution:
The `bugSolution.html` file demonstrates the correct approach of storing the original innerHTML in a variable before appending new content.