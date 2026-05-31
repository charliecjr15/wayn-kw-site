# Wayn Cafe public static site

Static landing/support/privacy pages for `https://wayn-kw.com`.

## Free hosting recommendation

Use Cloudflare Pages free tier because it gives HTTPS, custom domain support, CDN, redirects, and easy DNS/email routing in the same place.

Settings:

- Project name: `wayn-cafe`
- Production branch: `main`
- Build command: leave blank
- Build output directory: `public-site`
- Custom domains: `wayn-kw.com` and `www.wayn-kw.com`

If using GitHub Pages instead:

- Publish from the `public-site` folder by copying these files to a `gh-pages` branch, or use a GitHub Action.
- Keep `public-site/CNAME` set to `wayn-kw.com`.
- DNS needs apex A records to GitHub Pages and a `www` CNAME to `<github-user>.github.io`.

## Required follow-up before store submission

- Make sure `support@wayn-kw.com` actually routes somewhere, for example with Cloudflare Email Routing.
- Publish and verify:
  - `https://wayn-kw.com/`
  - `https://wayn-kw.com/privacy/`
  - `https://wayn-kw.com/support/`
