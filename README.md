# Tailwind CSS @apply Directive Issue with Pseudo-selectors

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to apply styles when used with CSS pseudo-selectors such as `:hover`.  The expected hover styles are not applied, leading to broken functionality.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `bugSolution.css` to see how to work around the issue.

## Solution

The solution is to apply the styles directly instead of using `@apply` with pseudo-selectors.  See `bugSolution.css` for the corrected implementation.