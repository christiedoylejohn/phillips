# Phillips Prototype

A self-contained single-file HTML/CSS/JS prototype. Open `index.html` directly in a browser, or deploy it to the web via Vercel.

## Deploy to Vercel through GitHub

1. **Create a GitHub repo** and push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial prototype"
   git branch -M main
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
2. **Import it on Vercel:** go to [vercel.com/new](https://vercel.com/new), pick the GitHub repo, and click **Deploy**. No build step or framework is needed — it's static.
3. **Every push to `main` redeploys automatically.** Pull requests get their own preview URLs.

## Structure

- `index.html` — the prototype (fonts loaded from the Google Fonts CDN, so it's fully self-contained)
- `vercel.json` — static hosting config (clean URLs)
