# Tarn

A single-page WebGL experience: a liquid-glass **Take me in** button floating on a rendered 3D deep-blue sea.
Drag to orbit, tap the water to make ripples, switch day/night and clear/rain/snow. Press the button and you
fall onto it like a stone and sink with it into the deep, where the page is printed on a sheet of paper
hanging underwater.

No build step: everything is in `index.html` (inline CSS, JS and GLSL; Google Fonts for type).

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Static site. On Vercel: import the repo, framework preset **Other**, no build command, no output directory.
