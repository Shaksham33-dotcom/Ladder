# Ladder — Every Home Climbs

Concept app for **STRATEGEM '26** (MANTHAN, COER University, Roorkee) by **Shaksham Kumar Gupta**.

Ladder is a three-rung home-services venture:
- **Rung 1 · Emergency** — electrician/plumber/carpenter/AC tech in 20–30 min, ₹350 fixed
- **Rung 2 · Projects** — wiring, fit-outs, renovations with a signed deadline (5% back if late)
- **Rung 3 · Construction** — full home builds with customer-chosen branded materials

This repository is a **PWA (installable web app)** — login + OTP, property profiles
(home / cafe / factory / office / site), materials shop with search, brand filters, sorting and cart, address book,
order tracking, and a support chatbot. All demo data; no real backend.

## Run it on GitHub Pages (5 minutes)

1. Create a GitHub account (github.com) if you don't have one.
2. Click **+** (top right) → **New repository** → name it `ladder-app` → Public → **Create**.
3. On the repo page click **uploading an existing file** and drag ALL files from this folder
   (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, and the `icons/` folder), then **Commit changes**.
   (Keep `icons/` as a folder — the logo paths depend on it.)
4. Go to **Settings → Pages** → under "Build and deployment" choose **Deploy from a branch**,
   branch `main`, folder `/ (root)` → **Save**.
5. Wait ~1 minute. Your app is live at:
   `https://YOUR-USERNAME.github.io/ladder-app/`

## Install it as an app on your phone

- Open the link above in Chrome on Android → menu (⋮) → **Add to Home screen / Install app**.
- On iPhone (Safari) → Share → **Add to Home Screen**.
- It launches full-screen with the Ladder logo, works offline after the first visit,
  and behaves like a real installed app.

## Demo login

Any 10-digit phone number + OTP **1234**.

## Folder structure

```
index.html            the whole app (HTML+CSS+JS, self-contained)
manifest.webmanifest  PWA identity (name, colours, icons)
sw.js                 service worker (offline caching)
icons/                logo (white ladder on teal) — SVG + PNG sizes
```

## Customising

- Change the pilot zone / pricing: search `Lajpat Nagar`, `₹350`, `350` in `index.html`.
- Change colours: edit the CSS variables at the top of `index.html` (`--pri`, `--amb`, ...).
- Logo source: `icons/logo.svg` (edit in any vector editor, re-export PNGs if needed).

## Installing on your phone

Installing works only from the **live GitHub Pages link** (https://...), not from a locally opened file. Open the link on your phone, then:
- **Android (Chrome):** menu (⋮) → *Add to Home screen* → Install
- **iPhone (Safari):** Share → *Add to Home Screen*

If an old icon on your home screen won't open, delete it and add it again from the live link.
