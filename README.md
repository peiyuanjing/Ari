# For Ari ♡

A little Zürich restaurant picker, based on the Yuki date-page layout.

## Publish with GitHub Pages

1. Create a public GitHub repository (e.g. `for-ari`).
2. Upload `index.html`, `style.css`, `script.js` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Visit `https://YOUR-USERNAME.github.io/for-ari/` after deployment.

## Customize

- In `script.js`, edit `dateOptions` and `timeOptions` before sharing the link.
- In `index.html`, edit restaurant descriptions and menu links if needed.
- The gradient restaurant images are deliberately decorative placeholders, **not actual restaurant photographs**. To add your own licensed photos, replace each `<div class="restaurant-photo ...">...</div>` with an `<img class="restaurant-photo" src="images/dar.jpg" alt="DAR restaurant interior" loading="lazy">` and add `object-fit:cover;width:100%` to `.restaurant-photo` in `style.css`.
- Prices are planning guidance, not guaranteed current menu prices. Check menus, vegetarian options, and availability before booking.

No framework, backend, or dependencies required. The Copy button copies Ari's selection; it does not send a message or reserve a table.
