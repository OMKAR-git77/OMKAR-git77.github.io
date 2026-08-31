# Omkar Rikke — Portfolio (GitHub Pages)

Static portfolio site for [OMKAR-git77](https://github.com/OMKAR-git77).

Live URL after you enable Pages:

- User site: `https://omkar-git77.github.io/`
- Or project site: `https://omkar-git77.github.io/<repo-name>/`

## Deploy on GitHub Pages (recommended)

### Option A — user site (best URL)

1. Create a **public** repository named exactly:
   ```
   OMKAR-git77.github.io
   ```
2. Upload every file in this folder to the repo root (`index.html`, `styles.css`, `script.js`).
3. GitHub → repo **Settings** → **Pages**.
4. Source: **Deploy from a branch** → `main` → `/ (root)` → Save.
5. Wait 1–2 minutes, then open `https://OMKAR-git77.github.io/`.

### Option B — project site

1. Create any public repo (example: `portfolio`).
2. Upload these files to the root.
3. Settings → Pages → `main` / root.
4. Site will be at `https://OMKAR-git77.github.io/portfolio/`.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Customize

- Bio / location: `index.html` hero and about sections
- Projects: the `#projects` cards
- Links: GitHub + LinkedIn already point at your real profiles
- Colors: CSS variables in `styles.css` (`--accent`, `--bg`)

No build step. No Node. Pure HTML / CSS / JS.
