# Mouse Trail Canvas

A 1440×920 canvas where a thin line trails behind your mouse, with live controls tucked into a Settings menu. Pure HTML/CSS/JS — no build step, no dependencies.

**[Live demo](https://joshofcourse.github.io/mouse-trail-canvas/)**

## Features

- Thin trailing line that follows the cursor with adjustable easing (Smoothing)
- Settings menu: trail length, thickness, fade, smoothing, stroke color, plus Taper / Rainbow / Glow toggles
- Custom background image (upload button)
- **Save as default** — your current settings and background are remembered via `localStorage` and reload automatically

## Set a default background

Drop an image named `background.jpg` next to `index.html` and it loads as the default backdrop. Or use the in-page **Background** button and hit **Save as default** to store one in the browser.

## Run locally

Just open `index.html` in a browser — that's it.

## Hosting on GitHub Pages

1. Push this folder to a GitHub repo.
2. Repo **Settings → Pages → Build and deployment**, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Your site goes live at `https://YOUR_USERNAME.github.io/mouse-trail-canvas/`.
