# Sweet Tetris 🍭

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

## Put it on the internet (GitHub Pages)

1. Create a new **empty** repo on GitHub named `tetris` (no README).
2. From this folder:

   ```bash
   git remote add origin https://github.com/<your-username>/tetris.git
   git branch -M main
   git push -u origin main
   ```

3. Repo → **Settings → Pages** → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Live at `https://<your-username>.github.io/tetris/` within a minute.
