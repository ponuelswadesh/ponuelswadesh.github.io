# Ponuel Mollah Swadesh | Research Portfolio

Static website. No build step, no framework, no dependencies.

- `index.html` is the whole site (HTML, CSS and a small script for the filters).
- `assets/` holds the portrait, the share image, the CV and the certificate files.

## Preview locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Hosted with GitHub Pages at https://ponuelswadesh.github.io (the repository must be named `ponuelswadesh.github.io`).
In Settings, then Pages, choose "Deploy from a branch", `main` and `/ (root)`. No build step is needed.
