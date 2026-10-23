# Seven Sunday Company Ltd website
Static site (HTML, CSS, JavaScript). Runs on GitHub Pages with no build step.

## Publish
1. Upload the **contents** of this folder to a GitHub repo (keep `.nojekyll`).
2. Settings → Pages → Deploy from branch → `main` / `(root)`.
3. Open `https://<username>.github.io/<repo>/`.

## Add the real details (`app.js`, top of the file)
`phone`, `whatsapp` (e.g. `2547XXXXXXXX`), `email`. Blank items stay hidden. Quote forms send to WhatsApp, or email if no WhatsApp is set. The location pin (-1.4324124, 36.9818785) and the Google Maps link are already set.

## Add the real photos (`images/`)
Pictures are drawn in code until you add photos. Save photos into `images/` with these names (.jpg, .jpeg, .png or .webp) and they replace the drawings automatically:
- `hero`: main banner
- `product1` … `product12`: product cards, in the order they appear under "All"
- `map1` … `map4`: the four pictures beside the map

## Edit the products and text
`PRODUCTS`, `FAQ`, `STEPS`, `WHY` and `BEN` are lists near the top of `app.js`. The products and wording are typical roofing-supply content; replace them with the company's actual stock, brands, profiles and gauges before launch.

## Roof calculator
Estimates sheets, ridge capping, gutter and screws for a standard two-slope roof from building size, pitch, overhang, sheet length and cover width. It is an estimate only.
