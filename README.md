# 2600 S 25th Broadview — interactive deck

Web version of the Lightstone working analysis (November 2026), laid out on a 1920×1080 artboard that scales to fit the screen.

- `index.html` — slides (each `<section class="slide">` is one slide)
- `deck.css` — styling; `--topo-wash` sets how faint the white topo background is
- `deck.js` — navigation, animations, lightbox. Paste the pending links into `LINKS` at the top
- `img/` — photos, textures, floor plans

No build step. Netlify publishes the repo root (see `netlify.toml`). Arrow keys or space move between slides; **M** opens the contents.
