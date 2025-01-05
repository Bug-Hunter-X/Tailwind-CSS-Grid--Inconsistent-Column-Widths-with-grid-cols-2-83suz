# Tailwind CSS Grid - Inconsistent Column Widths

This repository demonstrates a bug encountered when using Tailwind CSS's grid system, specifically with `grid-cols-2`.  The issue manifests as inconsistent column widths, where the second column unexpectedly occupies more space than the first, disrupting the intended layout.

The bug is particularly noticeable with dynamic content or complex layouts, making it difficult to reliably reproduce. The provided example shows a simple scenario, however the actual problem might show up with less obvious elements in the layout.

## Bug Reproduction

1. Clone this repository.
2. Run a development server (e.g., using Vite or Next.js).
3. Observe the rendered layout in the browser.
4. You may need to experiment with the text content of each div to observe the effect (try adding substantially more text to the left div for example).

## Solution

The solution file provides possible workarounds involving more specific class names to control the width of grid elements.  This solution highlights the importance of careful consideration of content size and potential layout adjustments when working with Tailwind CSS grids.