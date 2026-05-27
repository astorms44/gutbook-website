# gutbook-website

Static landing + privacy + support pages for Gutbook.

## Files
- `index.html` — landing page
- `privacy.html` — privacy policy (linked from App Store Connect)
- `support.html` — support page (linked from App Store Connect)
- `style.css` — shared stylesheet

## Deploy to GitHub Pages

1. Create a new **public** repo on github.com named `gutbook-website` (or any name).
2. From this folder, push:
   ```bash
   cd "/Users/austinstorms/Documents/Custom Software/IBSTracker/gutbook-website"
   git init
   git add .
   git commit -m "Initial Gutbook site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/gutbook-website.git
   git push -u origin main
   ```
3. On github.com → repo → **Settings → Pages**.
4. Source: **Deploy from a branch**. Branch: **main**, folder: **/ (root)**. Save.
5. Wait ~1 min. GitHub will show the URL (e.g. `https://<your-username>.github.io/gutbook-website/`).
6. Verify these resolve:
   - `https://<your-username>.github.io/gutbook-website/`
   - `https://<your-username>.github.io/gutbook-website/privacy.html`
   - `https://<your-username>.github.io/gutbook-website/support.html`

These two URLs go into App Store Connect → App Information → Privacy Policy URL + Support URL.
