# Skeleton Table Loading Rows

## What does this do?

This example shows table-shaped skeleton rows while data is loading.

## How is it used?

Add rows with placeholder cells:

```html
<div class="skeleton-row">
  <span class="skeleton-cell wide"></span>
  <span class="skeleton-cell short"></span>
  <span class="skeleton-cell"></span>
</div>
```

## Why is it useful?

Dashboards and admin panels often load table data asynchronously. Skeleton rows keep the layout stable and make waiting feel intentional.

## Features

- Table-style placeholder rows
- Shimmer loading animation
- Responsive stacked layout
- Pure HTML and CSS
- `prefers-reduced-motion` support

## Tech Stack

- HTML
- CSS

## Preview

Open `demo.html` directly in a browser to view the example.

## Contribution Notes

- Proposed for issue #11155
- All files are scoped to this submission folder
- No framework source files are modified
