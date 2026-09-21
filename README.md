# Hybrid Arena — 1-on-1

Live site (GitHub Pages):

**https://kaisaanabdul-rahman.github.io/hybrid-arena/**

Repo: https://github.com/kaisaanabdul-rahman/hybrid-arena

## If the live URL 404s

GitHub Pages sometimes needs one click the first time:

1. Open https://github.com/kaisaanabdul-rahman/hybrid-arena/settings/pages
2. Under **Build and deployment**:
   - Source: **GitHub Actions** (preferred), or **Deploy from a branch** → `main` / `/ (root)`
3. Wait 1–2 minutes and refresh the live URL.

## Local preview

Open `index.html` in a browser. No build step.

## Intake

- First visit shows only the form.
- Valid submit unlocks training details and stores the unlock in `sessionStorage`.
- Leads are saved to `localStorage` (`ha_leads`) and logged to the console.

## Booking email

In `index.html`:

```js
var BOOKING_EMAIL = "kaisaanabdul@gmail.com";
var BOOKING_SUBJECT = "1-on-1 Training Inquiry";
```
