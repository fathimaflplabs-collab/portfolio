# Fathima Shirin P J — Portfolio Website

A single-page professional portfolio built with plain HTML, CSS and a touch of JavaScript (no build tools required).

## Files
- `index.html` — the full page (structure + styles + script in one file, except the photo)
- `assets/photo.jpg` — profile photo used in the hero section

## How to use
1. Keep `index.html` and the `assets/` folder together in the same directory.
2. Open `index.html` directly in any browser, or upload the whole folder to any static host
   (GitHub Pages, Netlify, Vercel, etc.).
3. To update content, edit the text inside `index.html` — each section is clearly commented
   with an id (`#about`, `#experience`, `#skills`, `#projects`, `#education`, `#achievements`, `#contact`).
4. To change the photo, replace `assets/photo.jpg` with a new image of the same name (or update
   the `src` in the `.portrait-frame img` tag in `index.html`).

## Fonts
Loaded from Google Fonts (Fraunces for headings, Inter for body text) — requires an internet
connection when the page is viewed. To make it fully offline, download the font files and
update the `<link>` tags and `font-family` references.
