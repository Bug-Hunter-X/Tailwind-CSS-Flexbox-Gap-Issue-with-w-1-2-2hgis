# Tailwind CSS Flexbox Gap Issue

This repository demonstrates a subtle issue that can occur when using Tailwind CSS's `w-1/2` utility class within a flex container.  Due to rounding or spacing inconsistencies, a small gap may appear between the flex items.

The `bug.html` file showcases the problem, while `bugSolution.html` provides a potential solution.  The problem is particularly noticeable when dealing with fractional widths in flexbox layouts.  This issue is not specific to a particular version of Tailwind but is a consequence of the interaction between flexbox and fractional width units.