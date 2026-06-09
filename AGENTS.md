# AGENTS.md — ashfallsoftware.com

Static landing page for Ashfall Software. No build step, no framework, no CI.

## Dev server

```bash
python3 -m http.server 8000
```

Or open `index.html` directly.

## Asset notes

- `assets/fishing.gif` — pixel art sourced from `../indie-seishun/main/game/assets/`. If replacing GIFs, keep `image-rendering: pixelated` on `<img>` elements in the CSS to preserve crisp pixel art at non-native sizes.
- All CSS is inline in `index.html`. No external stylesheets or build pipeline.
