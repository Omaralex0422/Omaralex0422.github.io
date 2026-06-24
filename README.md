# Omar Arroyo — Portfolio

Live site: **https://omaralex0422.github.io**

A single-page portfolio. It renders client-side (the `support.js` runtime loads
React from a CDN and hydrates the page), so it runs as plain static files — no
build step or server needed.

## Files
- `index.html` — what the website serves (a copy of `Omar Arroyo.dc.html`).
- `Omar Arroyo.dc.html` — the editable design-canvas source.
- `image-slot.js` — the fillable image containers.
- `support.js` — the rendering runtime.
- `images/` — every photo on the site. See `images/README.md` for the naming.

## Updating photos
Drop a correctly-named file into `images/` (e.g. `portrait.jpg`, `shot-mmg.png`)
and commit. Names are listed in `images/README.md`.

## Updating the design
Edit `Omar Arroyo.dc.html`, then re-sync the served copy and push:

```bash
cp "Omar Arroyo.dc.html" index.html
git add -A && git commit -m "Update site" && git push
```

GitHub Pages redeploys automatically a minute or so after each push.
