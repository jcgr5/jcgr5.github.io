# AGENTS.md

## What this is

Vanilla HTML/CSS/JS static portfolio site deployed via **GitHub Pages** (`jcgr5.github.io`). No frameworks, no package manager, no build step.

## Key structure

- `index.html` — single-page portfolio (entrypoint)
- `styles/style.css` — all styles
- `scripts/script.js` — recommendation form popup logic
- `html_finalprojimages/` — static image assets

## Deployment

- Pushes to `main` auto-deploy to GitHub Pages (user site).
- No CI workflows or deploy scripts exist.

## Commands

- **Preview locally:** open `index.html` in a browser (no server needed, but a local server like `python3 -m http.server` avoids CORS edge cases).
- **No tests, linters, typecheckers, or formatters configured.**

## Conventions

- Branch naming: `feature/` prefix for feature branches (e.g., `feature/Practica_display_grid`).
- `.xopp` files are Xournal++ notes, not code.
