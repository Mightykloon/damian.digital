# damian.digital

Personal portfolio of Damian Dueñas — Design Director.

Successor to `damiangduenas.me` (domain lapsed in 2026; the old deploy still lives at
`damians-hyperlinks.netlify.app`). Refreshed for the new domain **https://www.damian.digital**
with a flat black, blueprint-grid theme (Geist + Geist Mono).

## Stack

Zero-build static site: a single `index.html` with inline CSS/JS, plus `img/` assets.
No build step — deploy the folder as-is. Animation uses Anime.js v4 and Motion, loaded as
pinned ESM modules from jsDelivr; the page stays fully readable if they fail to load.

## Local preview

```
python -m http.server 4173
```

## Deploy

Netlify (drag-and-drop or connect this repo; publish directory is the repo root).
Point `damian.digital` DNS at Netlify and set the primary domain in the site settings.
