# Theotember

A one-page dictionary entry for the word *Theotember*.

Live at: https://theoleburu.github.io/theotember/

## Publishing

```bash
git init
git add .
git commit -m "Define Theotember"
git branch -M main
git remote add origin https://github.com/TheoLeburu/theotember.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
Give it 1–2 minutes to build.

## Getting it into Google

1. Open Search Console at https://search.google.com/search-console and add
   `https://theoleburu.github.io/theotember/` as a URL-prefix property.
   Verification is automatic for GitHub Pages under your own account in most
   cases; if not, use the HTML file method and drop the file next to index.html.
2. Paste the URL into the inspection bar at the top, then click
   **Request indexing**.
3. Submit `sitemap.xml` under **Sitemaps**.
4. Test the structured data at https://search.google.com/test/rich-results

## If you change the URL

The canonical URL appears in five places — `index.html` (canonical link, two
og: tags, and twice in the JSON-LD), plus `sitemap.xml` and `robots.txt`.
Update all of them or Google will index the wrong address.
