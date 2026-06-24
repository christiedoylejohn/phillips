# Saleroom

A self-contained single-file HTML/CSS/JS prototype of the Phillips **Saleroom — Lot view**: a mobile live-auction bidding interface. Open `index.html` directly in a browser, or deploy it to the web via Vercel.

## Deploy to Vercel through GitHub

1. **Push this folder** to GitHub (already wired to `origin`):
   ```bash
   git add .
   git commit -m "Update prototype"
   git push
   ```
2. **Import it on Vercel:** go to [vercel.com/new](https://vercel.com/new), pick the GitHub repo, and click **Deploy**. No build step or framework is needed — it's static.
3. **Every push to `main` redeploys automatically.** Pull requests get their own preview URLs.

## Structure

- `index.html` — the Saleroom lot-view prototype (fonts loaded from the Google Fonts CDN, so it's fully self-contained)
- `vercel.json` — static hosting config (clean URLs)
