# Uncommon CSS Bugs and Quirks

This repository demonstrates some less common but potentially tricky bugs that can occur in CSS.  It focuses on unexpected behavior with the `calc()` function and the `box-sizing` property.

## Bug 1: `calc()` and Unexpected Results

The `bug.css` file shows an example where `calc()` produces unexpected results due to unit inconsistencies and the lack of a defined parent width.

## Bug 2: `box-sizing` and Layout Issues

The same file also illustrates problems that arise from using `box-sizing: border-box;` without a full understanding of its impact on padding and borders.

## Solutions

`bugSolution.css` offers corrected versions of the CSS, demonstrating how to solve these issues.  Always ensure your units are consistent in `calc()` expressions and explicitly define parent container widths if using percentage-based calculations.