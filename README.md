# AgNova website

A single-page site for the AgNova autonomous planting robot. No build step: just static files.

- `index.html` — the whole page (text, styles and scripts)
- `assets/` — logo, videos and video cover images

## Put it on GitHub Pages

1. Create a new **public** repository on GitHub, for example `agnova`.
2. Upload `index.html` and the `assets` folder to it (Add file → Upload files).
3. Go to Settings → Pages. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/agnova/`.

## Change the text or videos

Open `index.html` in any text editor and edit the words. To swap a video, replace the file in `assets/` and keep the same file name.
