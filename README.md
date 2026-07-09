# kube-flexbox

Combines [Kube 6.5](https://imperavi.com/kube/) with [Flexbox-Grid](http://flexboxgrid.com), replacing Kube's built-in grid system with a modern flexbox alternative.

## Quick start

Link the CSS (and optionally the JS) in your HTML:

```html
<link rel="stylesheet" href="dist/kube-flexbox.css">

<!-- Optional: required for tabs, modal, dropdown, collapse, and message components -->
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="dist/kube-flexbox.js"></script>
```

Or install via npm:

```
npm install kube-flexbox --save
```

## What's included

**CSS** (`dist/kube-flexbox.css` / `.min.css`): Flexbox-Grid + full Kube stylesheet.

**JS** (`dist/kube-flexbox.js` / `.min.js`): Kube's interactive components. Requires jQuery. Covers:
- Tabs
- Collapse / accordion
- Modal
- Dropdown
- Dismissible messages
- Offcanvas
- Sticky
- Toggleme

## Removing unused components

Edit `src/kube/src/_scss/_components.scss` and comment out any components you don't need, then rebuild:

```
npm install
npm run build
```

## Building from source

```
npm install
npm run build
```

To preview locally:

```
npx serve .
```

## Details

kube-flexbox replaces Kube's grid with Flexbox-Grid to provide:
1. A modern flexbox-based 12-column grid
2. Kube's full component set (typography, buttons, forms, tables, labels, modals, etc.)
3. No conflicts between the two frameworks

For Flexbox-Grid documentation: http://flexboxgrid.com
