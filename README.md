# Pricing Page Maker

Free micro-tool from **Indie Agent Kit** (`boltdoesthis`).

Enter a product name, three plan names, prices, and feature bullets. Preview a clean pricing section, then download a standalone HTML page (or copy just the section snippet). Everything runs in the browser. No build step, no accounts, no paid APIs.

**Live demo:** https://boltdoesthis.github.io/pricing-page-maker/

## Need it done for you?

Fixed-price micro-help (landing pages, launch packs, skill packs): https://boltdoesthis.github.io/indie-agent-services/

Email: [boltdoesthis@gmail.com](mailto:boltdoesthis@gmail.com)

## Features

- Form inputs for product name, tagline, currency, and three plans (name, price, period, CTA, feature bullets)
- Live preview of a clean pricing section
- Three themes: Ink, Mint, Paper
- Download a full standalone HTML page, or copy a drop-in section snippet
- Mark one plan as Featured
- Static files only. Works on GitHub Pages, Cloudflare Pages, Netlify, or any static host

## Files

| File | Role |
|------|------|
| `index.html` | App (HTML + CSS + JS in one file) |
| `README.md` | This file |

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python3 -m http.server 8080

# Node (if you have npx)
npx --yes serve -p 8080
```

Then visit `http://localhost:8080`.

## Deploy (free)

### GitHub Pages (boltdoesthis / pricing-page-maker)

1. Create a public repo named `pricing-page-maker` under [github.com/boltdoesthis](https://github.com/boltdoesthis).
2. Push this folder as the repo root (or put files in `/docs` and set Pages source to `/docs`).
3. Settings → Pages → Deploy from branch → `main` / root (or `/docs`).
4. Site URL: `https://boltdoesthis.github.io/pricing-page-maker/`

### Cloudflare Pages

1. Push the same repo to GitHub/GitLab.
2. Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Framework preset: **None**. Build command: empty. Output directory: `/` (repo root).
4. Deploy. Optional: attach a custom domain later.

## Related

- README to Landing: https://boltdoesthis.github.io/readme-to-landing/
- Changelog to OG: https://boltdoesthis.github.io/changelog-to-og/
- Services: https://boltdoesthis.github.io/indie-agent-services/

## License

MIT. Indie Agent Kit / boltdoesthis.

## Brand

Public brand only: **Indie Agent Kit** / **boltdoesthis**.
