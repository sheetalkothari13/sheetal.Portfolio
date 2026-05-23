# Sheetal Kothari — Portfolio

This is a single-file static portfolio (HTML/CSS/JS) ready for deployment on Vercel.

Quick deploy (GitHub integration):

1. Push this repository to GitHub.
2. In Vercel, import the GitHub repository and set the root to the repository root.
3. Vercel will detect the static files and deploy automatically. The site root will serve `sheetal_kothari_portfolio.html`.

Or via Vercel CLI:

```bash
npm run deploy
# or
npx vercel --prod
```

Notes:
- `vercel.json` maps `/` to `sheetal_kothari_portfolio.html` and exposes static `assets/`.
- If you want a different entry filename, update `vercel.json` routes.
