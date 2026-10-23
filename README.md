# Ten Years Away – static copy

Plain static site (no build step). Open `index.html` through any static web server.

```
index.html      page markup
css/style.css   all styles (fonts + noise texture referenced relatively)
js/             app scripts (React / three.js / GSAP bundles, already compiled)
fonts/          PP Valve woff2 files
textures/       noise.webp
404.html        fallback for GitHub Pages
.nojekyll       stops GitHub Pages from running Jekyll
```

## Run locally
```
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy on GitHub Pages
Settings → Pages → Deploy from branch → `main` / root.

## Notes
- Comic page images and textures are loaded from `admin10.375.studio` (not bundled).
- Only the home page was captured; `/en/year` and `/en/about` are not included.
- Original design and artwork belong to Studio375 / Davide Grazi – use with permission and credit.
