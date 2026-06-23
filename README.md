# Johna Gravitt — Portfolio Site

Personal professional portfolio site built with the Spiritbird Productions "Midnight Cosmos" brand palette.

## Files

- `index.html` — Complete single-page site (self-contained, inline CSS, no external dependencies)
- `spiritbird-logo.jpg` — Spiritbird Productions logo
- `README.md` — This file

## Color Palette & Contrast Audit

All color pairings pass **WCAG AAA** standards.

| Usage | Color | Hex | Contrast vs Background | Level |
|-------|-------|-----|----------------------|-------|
| Background | Midnight Navy | `#0B1026` | — | — |
| Name / Links | Turquoise | `#40E0D0` | 11.46:1 | AAA ✓ |
| Section Headings | Mint Green | `#98FF98` | 15.31:1 | AAA ✓ |
| Body Text | White | `#FFFFFF` | 18.81:1 | AAA ✓ |
| Secondary Text | Powder Blue | `#B0D4F1` | 12.12:1 | AAA ✓ |
| Accents (text) | Rose Gold (adj) | `#CA959D` | 7.43:1 | AAA ✓ |
| Dividers (non-text) | Rose Gold | `#B76E79` | 4.94:1 | 1.4.11 ✓ |

## Accessibility Features

- Skip-to-content link (first focusable element)
- Semantic HTML5: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Proper heading hierarchy: single H1 → H2 → H3
- ARIA landmarks and `aria-labelledby` on all sections
- Visible `:focus-visible` indicators (turquoise outline)
- `prefers-reduced-motion` respected
- All images have descriptive `alt` text
- Keyboard-navigable nav with logical tab order
- Screen-reader-only content uses `.sr-only` class
- No auto-playing media, no JavaScript required

## Deployment (GitHub Pages)

1. Create a repository on GitHub (e.g., `spiritbird73.github.io` for the user site, or any repo name)
2. Push `index.html` and `spiritbird-logo.jpg` to the `main` branch
3. In repo Settings → Pages, set Source to "Deploy from a branch" → `main` → `/ (root)`
4. Site will be live at `https://spiritbird73.github.io/` (user site) or `https://spiritbird73.github.io/<repo-name>/`

### For custom domain (optional, $12/year):
5. Purchase domain (e.g., johnagravitt.com) from any registrar
6. Add a `CNAME` file to the repo containing the domain name
7. Configure DNS records per GitHub's docs

## To Update

Edit `index.html` directly and push. No build step needed — it's a single static HTML file.
