# DilSeCanvas New

Personalised digital gifts — static website (latest version, v49).

## What's inside

- `index.html` — the whole site in ONE file (13,924 lines): all HTML, CSS and
  JavaScript inline. There are no separate .js or .css files — all 57 gifts,
  7 games, routing and share-link logic live inside this file.
- `assets/` — 122 photos used by the gifts and games (105 WebP + 17 JPG, ~23 MB)

## Run locally

Serve the folder with any static server, or open `index.html` in a browser.
Example: `npx serve .` or `python3 -m http.server`

## Deploy

Any static host works (Firebase Hosting, Netlify, GitHub Pages, ...).
Upload the folder contents as-is; `index.html` is the entry point.

## Notes

- No backend yet. Gift sharing links and multiplayer games need a Firebase
  project (Hosting + Firestore) — not included here.
- Keep private keys out of this repo. Only code, Firestore rules and the
  Firebase web config belong here.
