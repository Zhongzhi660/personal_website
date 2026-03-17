# Zhongzhi Li - Academic Homepage

Static single-page site (Jon Barron / Yandong Ji / Tianxing Wu style). Deploy the contents to your GitHub Pages repo (e.g. zhongzhili.github.io).

## Before publishing

1. **Profile photo**: Add your photo as `images/me.jpg` (160×160 or square recommended).
2. **Resume**: Add `data/resume.pdf` if you use the Resume link.
3. **Links in `index.html`**: Replace `your.email@example.com`, `YOUR_ID` in the Google Scholar URL, and any other placeholders.
4. **Publications**: Replace the placeholder text under "Publications" with real paper entries (title, authors, venue, links, description). Use the commented HTML example in `index.html` for each paper; add thumbnails to `images/` if desired.

## Local preview

Open `index.html` in a browser, or use a local server (e.g. `python -m http.server 8000` in this directory).

## Deploy to GitHub Pages

Push this folder's contents to the default branch of your `zhongzhili.github.io` repository. If the repo previously used Hugo, switch to publishing this static folder (or remove Hugo config).
