# Flash — personal site

A small, fast personal site built with plain HTML, CSS and JavaScript. No build step.

## Files

- `index.html`, `about.html`, `notes.html`: pages
- `404.html`: shown for missing pages
- `style.css`: all styling (dark/light themes use CSS variables)
- `script.js`: theme toggle (Cmd/Ctrl + K) and GitHub contribution graph
- `favicon.svg`, `robots.txt`, `sitemap.xml`: site basics

## Setup checklist

- [ ] Set `GITHUB_USERNAME` at the top of `script.js`
- [ ] Replace placeholder social links and email in `index.html` and `about.html`
- [ ] Rewrite the About text and add real Notes
- [ ] Replace `your-domain.com` in `robots.txt` and `sitemap.xml`

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder
and visit http://localhost:8000.

## Deploy

Push to GitHub and enable Pages (Settings → Pages → `main` / root),
or drag the folder into Netlify or Cloudflare Pages.
