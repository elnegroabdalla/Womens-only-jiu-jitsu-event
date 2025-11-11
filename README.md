# Women's Jiu Jitsu Event

Simple static website for a women's-only jiu jitsu event. It includes a home page, an about page (locations and schedule), and a contact page with a contact form (placeholder only).

Files
- `index.html` — Home page
- `about.html` — About page (times & locations)
- `contact.html` — Contact page with placeholder photos and a simple JS form handler
- `styles.css` — Main styles
- `imgs/` — Image assets (placeholders)

How to run locally
1. Open `index.html` directly in your browser (double-click or `File > Open`).

OR, to serve via a simple HTTP server (recommended for testing relative links):

- Using Python 3:

```bash
cd path/to/wjjevent
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

- Using Node (if you have `http-server` installed):

```bash
npx http-server -c-1
```

Deployment
- The repo is already pushed to GitHub. You can deploy with GitHub Pages by enabling Pages in the repository settings and selecting the `main` branch (root) or by creating a `gh-pages` branch.

Notes & next steps
- Replace placeholder images with real photos in `imgs/`.
- Wire up the contact form to a real backend or an email service (e.g., Formspree, Netlify Forms).
- Consider adding a `.github/workflows/` workflow to automatically publish to GitHub Pages on push.

License
- Add a LICENSE file if you want to specify reuse terms.
