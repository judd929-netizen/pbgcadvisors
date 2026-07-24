# PBG Capital Advisors — Website

Single-page marketing site for **Palm Beach Gardens Capital Advisors LLC** (PBG Capital Advisors).
Everything lives in [`index.html`](index.html) (HTML + CSS + JS in one file). No build step.

- **Domain:** pbgcadvisors.com (set in [`CNAME`](CNAME))
- **Hosting:** GitHub Pages (deploys automatically on every push to `main`)
- **Contact form:** posts to FormSubmit → info@pbgcadvisors.com

## Deploy a change

Edit `index.html`, then:

```bash
git add -A
git commit -m "Describe the change"
git push
```

GitHub Pages rebuilds within ~1 minute. That's the whole deploy.

## Files
- `index.html` — the entire site
- `favicon.svg` — browser-tab icon (ascending bars mark)
- `PBG_Capital_Logo.svg` — standalone brand logo (for docs, email, decks)
- `Judd-appel.jpg` — team photo
- `CNAME` — custom domain for GitHub Pages
