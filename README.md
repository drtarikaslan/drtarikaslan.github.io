# Tarık ASLAN — Academic website

Static, dependency-free bilingual website for GitHub Pages.

- Turkish: `/`
- English: `/en/`
- Custom domain: `tarikaslan.com`
- Publish `main` branch, `/ (root)` in Settings → Pages.
- No build step, third-party fonts, cookies or analytics.

## Local preview

`python3 -m http.server 8765`

## Content updates

Edit `index.html` and `en/index.html` together. Shared styles are in `style.css`.
Only public professional information is included. Original CVs and private source documents are excluded.

## DNS

After setting the repository custom domain to tarikaslan.com:

| Type | Host | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | drtarikaslan.github.io |

Preserve unrelated MX/TXT records. Enable Enforce HTTPS once GitHub issues the certificate.
