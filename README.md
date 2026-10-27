# Drew Butler website (drewbutler.co.uk)

Copy of the live site, taken 25 Oct 2026 from GoHighLevel AI Studio so it can be hosted anywhere (e.g. Netlify, free).

## What's in `site/`
- `index.html`, `assets/` – the built site exactly as it runs live (all text and layout lives inside the minified JS file).
- `media/` – every image, video, 3D model and client logo the site uses, downloaded so nothing depends on GHL any more.
- `_redirects` – tells Netlify to serve the pages (/about, /gallery, /project/...) correctly.

## Deploy
Drag the `site` folder onto Netlify (app.netlify.com → Add new site → Deploy manually), then point the drewbutler.co.uk DNS at it.

## Contact form
Uses Netlify Forms (free up to 100 submissions/month). After the first deploy:
1. Netlify → site → **Forms** → **Enable form detection**, then redeploy.
2. Forms → **Form notifications** → add an email notification to Drew's address.
Submissions also appear under Forms → "contact".

## Known issues (also on the live site today)
1. **Three images on the AirPods project page are missing** – deleted on GHL's side, so they're broken on the live site too. Need re-supplying by Drew.
2. The NFF 3D model's preview "poster" points to an old WordPress image that no longer exists (harmless).
