# GlowNest — Demo Site (for Tracking practice)

3 pages: `index.html` (Home), `product.html` (Product), `thankyou.html` (Order confirmation).
No backend, no real payment — this exists purely to install GA4 / Google Tag on and practice tracking.

## How to put this live on GitHub Pages (free)

1. Go to https://github.com/Pratul89 and create a **new repository** — name it `glownest-site` (or anything you like). Keep it Public.
2. Open the new repo → click **"Add file" → "Upload files"**.
3. Drag in all files from this folder (`index.html`, `product.html`, `thankyou.html`, `style.css`, this `README.md`) → click **Commit changes**.
4. In the repo, go to **Settings → Pages**.
5. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main**, folder **/(root)** → Save.
6. Wait 1–2 minutes, then refresh — GitHub will show your live link, something like:
   `https://pratul89.github.io/glownest-site/`

That link is your real, live GlowNest demo site.

## Where the GA4 tag goes

Each HTML file has a comment block in `<head>` marking exactly where to paste your GA4 tag:

```html
<!-- GA4 TRACKING CODE GOES HERE -->
```

Paste the same Google tag (`gtag.js`) snippet in **all three pages**, right after that comment.
