# blink-brain/website

Marketing landing page for [Blink](https://github.com/blink-brain/blink), an AI executive function partner for people with ADHD.

Plain static HTML/CSS, no build step. Served via GitHub Pages at https://blink-brain.github.io/website/.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating brand assets

Source SVGs/PNGs live in `assets/` and are copied from the main [`blink`](https://github.com/blink-brain/blink) repo's `assets/branding/` directory. Keep them in sync if the brand kit changes there.
