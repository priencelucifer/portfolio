# Ricky Kashyap — Portfolio

Clean, editorial portfolio with light/dark themes. One HTML file, no framework, no build step.

- `index.html` — the whole site
- `404.html` — not-found page (also stops Cloudflare Pages from serving the homepage for every unknown URL)
- `_headers` — Cloudflare Pages headers: keeps `*.pages.dev` out of search results, caches icons
- `favicon.ico`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `site.webmanifest` — icons
- `og-image.png` — social sharing preview (1200×630)
- `robots.txt`, `sitemap.xml`, `llms.txt` — crawler and AI-assistant guidance
- `resume-ricky-kashyap.pdf` — CV (linked from the site)

Hosted on Cloudflare Pages; pushes to `main` auto-deploy.
