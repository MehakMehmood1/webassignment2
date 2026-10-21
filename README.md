# Web Developer Portfolio - Assignment #2

## What CSS Is and Its Benefits
CSS (Cascading Style Sheets) is the language that controls how HTML content looks. It separates design from structure, so one stylesheet can restyle many pages. Benefits include consistent design, less repeated code, easier maintenance, faster loading and responsive layouts.

## Selector, Property and Value
In `style.css` the rule `button:hover { background-color: #f0c9a5; }` has the selector `button:hover`, the property `background-color` and the value `#f0c9a5`.

## Inline, Embedded and External CSS
- **Inline** (`index.html`): the `style` attribute on one element. It is quick but hard to reuse.
- **Embedded** (`information.html`): rules inside a `<style>` element in the head, which apply to that page only.
- **External** (`registration.html`): a separate `style.css` linked with `<link>`. It is reusable across pages and the easiest to maintain.

## CSS1, CSS2/2.1 and Modern CSS
CSS1 (1996) introduced basic fonts, colours and margins. CSS2 (1998) and CSS2.1 added positioning, media types and tables. Modern CSS is split into modules such as selectors, flexbox, grid and colour, which are developed and released separately.

## Browser Support
Browsers can render the same CSS differently, so support matters for a consistent experience. I tested the site in Google Chrome and Microsoft Edge and noticed no major differences.

## Semantic and Non-Semantic HTML
- Semantic: `<nav>` in `index.html` describes the navigation links.
- Non-semantic: `<div class="button-row">` in `registration.html` only groups the buttons for styling.
