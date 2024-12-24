# CSS calc() Function Issue

This repository demonstrates a problem with the CSS `calc()` function where the calculated width of an element is not being applied correctly. The expected behavior is that the element's width should be 50% of its parent's width, but it's not rendering as expected.  The solution demonstrates how to properly use `calc()` to achieve the desired result by correctly handling unit conversions and avoiding common pitfalls.

## Bug Report
The bug lies in the incorrect application of the `calc()` function.  The initial implementation has a subtle error preventing the width calculation from working as intended. 

## Solution
The corrected implementation ensures that the units used within the `calc()` function are consistent, resolving the unexpected behaviour.