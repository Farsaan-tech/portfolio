# Farsaan Siddiqui Syed — Portfolio

This portfolio automatically opens the appropriate version based on the visitor's screen width.

## Versions

- `index.html` — automatic entry point
- `desktop.html` — desktop version
- `mobile.html` — mobile version

### Routing

- **768px and below:** mobile version
- **Above 768px:** desktop version

The router uses `window.matchMedia()` and screen width rather than user-agent detection.

## GitHub Pages

Keep `index.html` in the repository root. GitHub Pages will load it automatically and redirect visitors to the correct version.
