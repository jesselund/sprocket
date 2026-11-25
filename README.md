# Sprocket

Sprocket Financial Services, Inc. — Move Money Fast.

## Repository layout

- [`site/`](site/): the marketing website for [sprocket.financial](https://sprocket.financial). A static, responsive single page (`index.html`, `styles.css`), a placeholder privacy page, logo assets and the `CNAME` file for the custom domain. It loads its colors and fonts from `style-guide/tokens.css`.
- [`style-guide/`](style-guide/): the Sprocket brand and design system. The brand book (`README.md`), design tokens as CSS variables (`tokens.css`) and JSON (`tokens.json`), and logo files (`logos/`).
- [`.github/workflows/pages.yml`](.github/workflows/pages.yml): deploys the site to GitHub Pages on every push to `main` that changes `site/` or `style-guide/`. It copies `style-guide/tokens.css` into the published site, so brand changes carry through automatically.

## Previewing the site locally

From the repository root:

```sh
ln -s ../style-guide site/style-guide   # one time; this link is git-ignored
cd site && python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

GitHub Pages must be enabled with **Settings → Pages → Source: GitHub Actions**. Until a custom domain is set, the site is served at `https://jesselund.github.io/sprocket/`. To launch on `sprocket.financial`, set the custom domain in the same settings page and point the domain's DNS records at GitHub Pages.
