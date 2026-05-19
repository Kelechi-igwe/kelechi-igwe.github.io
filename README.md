# kelechi-igwe.github.io

This repository holds the MyST website for the personal academic portfolio of Kelechi Igwe.

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
