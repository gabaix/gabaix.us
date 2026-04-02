# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Workflow

Always commit and push to git after every change.

## Site Overview

Static website hosted at `gabaix.us` (GitHub Pages, CNAME configured). No build step — files are served directly.

**Structure:**
- `index.html` — homepage with links to sub-pages
- `styles.css` — shared stylesheet used by all pages
- `cookies/index.html` — cookie demo sub-page (uses `../styles.css`)

## Adding New Pages

Create a subdirectory with an `index.html` that links `../styles.css` and includes a `← Home` back-link. Add the page to the list in `index.html`.

## Deployment

Push to `master` — GitHub Pages deploys automatically.
