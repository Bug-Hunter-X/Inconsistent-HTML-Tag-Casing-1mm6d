# Inconsistent HTML Tag Casing

This repository demonstrates a subtle but important bug in HTML: inconsistent capitalization of tags. While HTML is generally case-insensitive, maintaining consistent lowercase casing is best practice for readability and compatibility with more strict parsers or validators.

The `bug.html` file showcases the error. The `bugSolution.html` file provides the corrected version.

This is an uncommon bug because it often doesn't produce immediate errors.  However, it can lead to unexpected rendering and validation issues, especially in large and complex projects.

## How to Reproduce

1. Open `bug.html` in your browser.
2. Inspect the HTML source to observe the capitalization issue.
3. Compare it with the corrected version in `bugSolution.html`.