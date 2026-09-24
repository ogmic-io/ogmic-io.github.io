# Ogmic website

Static company website for Ogmic, hosted at <https://www.ogmic.io> through GitHub Pages.

## Files

- `docs/index.html` — main page, with inline styling and a small script to update the copyright year.
- `docs/ogmic.png` — original wordmark and fallback asset. The page embeds this artwork as a mask so the light-and-gold version also works when opened locally in Safari.
- `docs/favicon.svg` — browser icon.
- `docs/dojo-ze-wordmark.svg` — official Dojo Zé vector wordmark with a transparent background and embedded brand font, adapted from the product’s branding assets.
- `docs/CNAME` and `docs/.nojekyll` — GitHub Pages configuration.

Open `docs/index.html` in a browser to preview. No dependencies or build step are required. GitHub Pages serves the `docs/` directory; local edits are not published until pushed through the repository’s deployment flow.
