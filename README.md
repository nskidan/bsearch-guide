# BSearch Technical Guide

A comprehensive technical reference for the BSearch enterprise search system, built as a static HTML site.

## Running Locally

**Option 1 — HTTP server (recommended for Mermaid diagrams):**

```bash
python -m http.server 8000 -d docs
# Open http://localhost:8000
```

**Option 2 — Open directly:**

Open `docs/index.html` in a browser. Note: Mermaid diagrams require an HTTP server (CDN scripts don't load from `file://`).

## Deployment

Deployed automatically to GitHub Pages via `.github/workflows/deploy.yml` on push to `main` (when files in `docs/` change).

## Structure

- `index.html` — Table of contents
- `chapter-01.html` through `chapter-13.html` — Guide content
- `styles.css` — Stylesheet (adapted from claude-code-guide)
