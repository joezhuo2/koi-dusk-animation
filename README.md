# Koi at Dusk

A koi swims a canal in a Chinese water town at dusk: stone bridge, tiled roofs, lantern reflections, ripples.

One self-contained `index.html`. Canvas 2D, vanilla JavaScript, no dependencies, no build step.

## Run

Open `index.html` in a browser.

Or serve the folder:

```bash
python -m http.server 8123
```

Then open http://localhost:8123.

## Notes

- Resizes with the window and scales for high-DPI screens.
- Draws a single still frame when `prefers-reduced-motion` is set.
