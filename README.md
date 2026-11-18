# SolarVeil Home Window Films

One-page website for SolarVeil Home Window Films, residential window film installers serving Denver and the Front Range.

## Files
- `index.html`: the full site, self-contained (styles, script and logo are inline).
- `assets/solarveil-logo.png`: original logo file.

## Quote form
The estimate form posts to FormSubmit and emails each request to **solarveilhomewindowfilms@gmail.com**.
The first submission after going live sends an activation email from FormSubmit to that inbox. Click **Activate** once; every request after that arrives normally.

## Contact
- Phone: (983) 208-6188
- Email: solarveilhomewindowfilms@gmail.com

## Hosting
Any static host works. For GitHub Pages: Settings → Pages → deploy from the `main` branch, root folder.

## Photos
Section photos are served from Unsplash (free to use under the Unsplash License). Swap the `images.unsplash.com` URLs in `index.html` for SolarVeil's own install photos when they're available.

## Pages
- `/` home page (`index.html`)
- `/privacy-policy` and `/terms` legal pages (styles in `assets/legal.css`)
- `googlea22f10d275b17c99.html` Google Search Console verification file. Keep it in the root, or Search Console will lose verification.
- `vercel.json` turns on clean URLs, so pages load without `.html`.
