# Chandana Bollimpalli — Portfolio

Static site, no build step. Four files:

```
chandana-portfolio/
├── index.html
├── style.css
├── script.js
└── assets/
    └── chandana.jpg
```

## Run locally
Open `index.html` directly in a browser, or serve the folder (e.g. `python3 -m http.server`) and visit it at `localhost`.

## Add it to a live GitHub Pages site
1. Copy all four items (`index.html`, `style.css`, `script.js`, `assets/`) into your repo — at the repo root if this is the whole site, or into a subfolder (e.g. `/portfolio`) if it's joining an existing site.
2. Commit and push.
3. If it's at the repo root and GitHub Pages is already enabled on that repo, it goes live at your existing Pages URL automatically. If it's in a subfolder, it's reachable at `<your-pages-url>/portfolio/`.

## What's editable
- Copy and resume content: inside `index.html` (experience bullets, skills chips, education, contact details).
- Colors, type, spacing: `style.css` — tokens are set once at the top under `:root`.
- Nav scroll-spy, mobile menu, copy-to-clipboard buttons: `script.js`.
- Photo: replace `assets/chandana.jpg` with a new image of the same name, or update the `src` in `index.html`'s `<img>` tag.
