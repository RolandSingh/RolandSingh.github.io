# Roland Singh — Academic Portfolio

Static three-page portfolio (no build step, no Jekyll): `index.html` (About), `publications.html`, `cv.html`.

## Deploy to GitHub Pages (5 minutes)

1. On GitHub, create a new **public** repository named exactly `<your-username>.github.io`
   (e.g. `RolandSingh.github.io`).
2. Upload everything in this folder (keep the folder structure: `assets/`, `files/`, `images/`).
3. Go to the repo's **Settings → Pages** and confirm Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`.
4. Wait 1–2 minutes. Your site is live at `https://<your-username>.github.io`.

## Add your photo

Put a square photo at `images/profile.jpg` (about 400×400 px). Until then, the site shows
an "RS" monogram automatically.

## Updating content

- **New publication** → copy one `<div class="pub">…</div>` block in `publications.html` and edit it.
  Badges: `badge accepted` (green), `badge review` (yellow), `badge prep` (blue).
- **New CV entry** → copy an `<div class="entry">…</div>` block in `cv.html`.
- **New CV PDF** → replace `files/Roland_Singh_CV.pdf` (keep the same filename).
- Colors/fonts live at the top of `assets/style.css` (`:root` variables).
