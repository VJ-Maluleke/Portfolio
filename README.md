# Honours Terms Portfolio (Google Sites embed)

This is a **single-file** portfolio page designed to be embedded into Google Sites.
All artwork is **inline SVG** (no external image files and no data URLs), so images cannot "go missing".

## Host it (recommended)
### Option A: Netlify Drop (fastest; works even if your GitHub repo is private)
1. Open Netlify Drop (search: “Netlify Drop”).
2. Drag `index.html` onto the page.
3. Copy the URL Netlify gives you.
4. Google Sites → Insert → Embed → By URL → paste the Netlify URL.

### Option B: GitHub Pages (repo must be **public** on most free plans)
1. Create a new repo and upload:
   - `index.html`
   - `.nojekyll`
2. Repo → Settings → Pages → Deploy from branch → `main` → `/(root)`
3. Use the published URL in Google Sites → Insert → Embed → By URL.

## Add your term submissions
Open `index.html` and edit the `CONFIG` object near the bottom.

For each term, paste:
- `items.report.url` → Drive file link OR Google Doc link
- `items.slides.url` → Google Slides link
- `items.video.url`  → YouTube link OR Drive video link

Drive previews require: **Anyone with the link → Viewer**.
