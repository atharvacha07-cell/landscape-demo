# Cheapscape Landscape — Website

Single-file marketing website for **Cheapscape Landscape** (Pittsburgh, PA).

## What's here
- `index.html` — the entire site (HTML + CSS + JS inline, no build step).

## Run locally
Just open `index.html` in a browser. Or serve it:
```bash
npx serve .
```

## Publish free with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` (and this `README.md`) to the repo root.
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)` → **Save**.
5. Site goes live at `https://<your-username>.github.io/<repo-name>/` in ~1 minute.

## Notes
- The hero uses a background video. Drop a file named `hero-video.mp4` next to `index.html` to enable it; until then a poster image shows.
- Photos load from Unsplash (need internet); a green/gold gradient shows as fallback if offline.
- Phone `(412) 500-4629` and the 4.9★ rating are from the Google listing. Email, hours, and the review text are placeholders — swap in real values.
