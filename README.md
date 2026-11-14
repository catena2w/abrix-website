---
purpose: Static one-page website for aBrix, served by GitHub Pages
---

# aBrix website

One static page: `index.html`, with brand files in `brand/` (brandbook PDF, logo pack ZIP, favicons, cover image). No build step.

- The contact form opens the visitor's email app with the message filled in; there is no backend.
- The page carries `<meta name="robots" content="noindex">` while it is a preview. Remove that line when the site goes live on its own domain.
- Fonts load from Google Fonts (Geist Mono, Inter).
