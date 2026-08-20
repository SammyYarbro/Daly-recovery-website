# dalyrecovery.org — public website

Static single-page site. One file, self-contained.

## Deploy to Cloudflare Pages

1. Create a GitHub repo named `daly-recovery-website`.
2. Copy every file in this folder into the repo root.
3. `git add . && git commit -m "initial" && git push`.
4. Cloudflare Pages → **Create → Pages → Connect to Git** → pick the repo.
5. Build command: *(leave blank)*. Build output directory: `.`
6. Deploy. Then Custom domains → add `dalyrecovery.org` and `www.dalyrecovery.org`.

## Files

- `index.html` — the entire site, inlined.
- `_headers` — Cloudflare Pages headers (security + caching).
- `_redirects` — clean-URL routing.
- `robots.txt` — search-engine allow.
- `sitemap.xml` — single-page sitemap.

## Editing content

Edit `Daly Recovery Website.dc.html` in the design project, re-bundle, replace `index.html` here, push.
