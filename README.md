# damian.digital

Personal portfolio of Damian Dueñas — Design Director.

Successor to `damiangduenas.me` (domain lapsed in 2026; the old deploy still lives at
`damians-hyperlinks.netlify.app`). Refreshed for the new domain **https://www.damian.digital**
with a black + reflective chrome/silver theme.

## Stack

Zero-build static site: a single `index.html` with inline CSS/JS, plus `img/` assets.
No dependencies, no build step — deploy the folder as-is.

## Local preview

```
python -m http.server 4173
```

## Deploy

Netlify (drag-and-drop or connect this repo; publish directory is the repo root).
Point `damian.digital` DNS at Netlify and set the primary domain in the site settings.
