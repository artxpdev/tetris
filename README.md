# Sweet Tetris 🍭

**Play: https://artxpdev.github.io/tetris/**

A candy-themed browser Tetris — single `index.html`, no build step, no dependencies.
Gummy blocks, floating sweets, and a candy shower every time you clear a line.

## Play locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173

## Controls

| Key | Action |
| --- | --- |
| ← → | Move |
| ↑ | Rotate |
| ↓ | Soft drop |
| Space | Hard drop |
| P | Pause |

Touch: swipe to move, swipe down to drop, tap to rotate.

## Install on your phone

Open the site in Safari (iOS) or Chrome (Android) → **Share → Add to Home Screen**.
It launches full-screen with the candy icon (`apple-touch-icon.png` / `manifest.webmanifest`).

## Deploy

Hosted on GitHub Pages from `main` / root. Any push to `main` redeploys within a minute:

```bash
git add -A && git commit -m "your message" && git push
```
