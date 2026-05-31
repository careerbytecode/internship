# CareerByteCode DevOps Internship

Standalone landing page for the DevOps Internship program.

## Files
- `index.html` — the landing page
- `shared-premium.css` — styles
- `shared-premium.js` — interactions (scroll reveals, counters, theme toggle, mobile nav)
- `cbc - logo.png` — logo / favicon

## Run locally
Any static server works, e.g.:
```
python -m http.server 8000
```
Then open http://localhost:8000

## Deploy (GitHub Pages)
1. Create a new GitHub repo (e.g. `internship`) and push these files to `main`.
2. Repo → Settings → Pages → Source: `main` branch, `/ (root)`.
3. Site goes live at `https://<user>.github.io/internship/`.

The `og:url` and `canonical` tags in `index.html` currently point to
`https://careerbytecode.github.io/internship/` — update them if the final URL
or a custom domain differs.

## Apply link
The "Apply" CTAs point to `https://wa.link/0nmn9p`. Swap this if a dedicated
internship WhatsApp link or application form is used.
