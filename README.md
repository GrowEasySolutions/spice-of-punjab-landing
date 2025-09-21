# Spice of Punjab – Landing Page (Vercel-ready)

This is a static, one-page website with a separate Menu page.

## Contents
- `index.html` – main landing page (relative image paths)
- `menu.html` – dynamic menu rendered from `menu.json`
- `menu.json` – menu data (edit prices/names here)
- `images/` – all placeholder images (replace with real photos later)

## Deploy
1. Upload everything to your GitHub repo (root).
2. Connect to Vercel → New Project → Framework: **Other** → Deploy.
3. Add custom domain in Vercel → update DNS at registrar.

## Notes
- Images use **relative paths** like `images/hero.jpg` to prevent loading issues.
- Update the contact form action in `index.html` to your **Formspree** endpoint.
- Edit `menu.json` to manage categories, items, descriptions, prices.
