# cursedbulletin.com — Website

Static one-page site. No build step, no server needed. Free hosting below.

## What's inside
- `index.html` — the whole page
- `style.css` — all styling (brand: black #0A0A0A, lime #B0FF00, Druk + Inter)
- `assets/` — mascot logo + favicon
- `fonts/` — Druk Condensed Super + Inter (brand fonts)

## Deploy FREE on Cloudflare Pages (15 min, lifetime free)

1. **Zip or upload this folder.** Go to dash.cloudflare.com → sign up free → Workers & Pages → Create → Pages → Upload assets. Drag this entire folder in. Name the project `cursedbulletin`.
2. **You get a free URL** like `cursedbulletin.pages.dev` — the site is live immediately.
3. **Connect your domain:** In the Pages project → Custom domains → Set up a custom domain → enter `cursedbulletin.com`. Cloudflare shows you 2 DNS records.
4. **Point DNS:** In Spaceship → domain → DNS → add the records Cloudflare shows (usually 2 CNAME/A records). Wait 5–30 min. Done — `cursedbulletin.com` shows your site.

(Netlify Drop works the same way if you prefer: app.netlify.com/drop — drag folder, then add custom domain.)

## Activate the tip form (2 min, free)
The tip form posts to Formspree. To receive tips:
1. Sign up free at formspree.io → create a form → copy your endpoint (looks like `https://formspree.io/f/abcdwxyz`)
2. In `index.html`, find `YOUR_FORM_ID` and replace with your endpoint.
3. Re-upload the folder to Cloudflare Pages (or it auto-updates if you connect a repo).

Until then, the form shows but won't deliver — the `tips@cursedbulletin.com` email link always works.

## Updating "Latest drops"
Edit the cards in `index.html` under `<!-- LATEST -->`: duplicate a card, change the headline, text, and Instagram post URL. Re-upload.
