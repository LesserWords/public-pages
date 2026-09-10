# public-pages

Static one-off HTML pages for Keroshop, served over **GitHub Pages**.

**Live:** https://lesserwords.github.io/public-pages/

## Pages

| Page | Live URL |
|------|----------|
| Index (hub) | https://lesserwords.github.io/public-pages/ |
| Briefing (sales one-pager) | https://lesserwords.github.io/public-pages/briefing.html |
| Progress (implementation status) | https://lesserwords.github.io/public-pages/progress.html |

## Add a new page

1. Drop a complete, standalone `.html` file in the repo root (with `<!doctype html>`, `<head>`, `<body>`).
2. Commit and push to `main`.
3. It appears on the index automatically — `index.html` lists every `.html` in the repo (except itself)
   via the public GitHub contents API, so there is no list to maintain. The card title is derived from
   the filename (`my-page.html` → "My Page").

GitHub Pages rebuilds in ~1–2 min after a push; hard-refresh if you see the old version.

## Notes

- `.nojekyll` disables Jekyll processing — files are served as-is.
- Pages source: `main` / root, HTTPS enforced.
- Everything here is **public**. Don't commit anything private.
