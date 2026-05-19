# kelechi-igwe.github.io

This repository contains an active academic portfolio website for Kelechi Igwe. The site is intentionally written as a work in progress while I continue to update research details, CV materials, and presentation assets.

## Website structure

- `index.md` — homepage
- `about.md` — CV / About page
- `publications.md`
- `presentations.md`
- `awards.md`
- `research/` — research project pages
- `_toc.yml` — site table of contents
- `myst.yml` — MyST configuration
- `.github/workflows/deploy.yml` — GitHub Pages deployment workflow

## Local preview

Install MyST:

```bash
npm install -g mystmd
```

Build the site:

```bash
myst build
```

## Deployment

The GitHub Action in `.github/workflows/deploy.yml` builds and deploys the site to GitHub Pages on every push to `main`.

This repository is being updated continuously as I refine the pages and add new content.
