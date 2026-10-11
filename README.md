# Form Elements

A static HTML page collection of common form widgets and UI interactions, built for web scraping and test-automation practice.

## About

Each page under `elements/` isolates one interaction (ajax load, autocomplete, drag and drop, file upload, modal, calendar, alert, broken link, right click, new tab, radio/checkbox, select list, infinite scroll) so it can be targeted individually by a scraper or automated test (e.g. Selenium, Playwright). Built November 2021.

## Features

- Plain HTML/CSS/JS pages, no build step
- One page per element/interaction, linked from `index.html`
- Bootstrap 5 and Font Awesome via CDN for styling

## Tech stack

- HTML, CSS, vanilla JavaScript
- Bootstrap 5 (CDN), Font Awesome (CDN)

## Project structure

```
index.html          # index linking to every element page
elements/            # one HTML file per form element / interaction
assets/css, assets/img
```

## Getting started

Open `index.html` directly in a browser, or serve the folder with any static file server:

```bash
npx serve .
```

## Status

Learning/practice project, not actively maintained.

## Related projects

- https://github.com/tolgazorlu/form-elements-last
