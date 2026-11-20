# Zarokê Musilman (زارۆکێ موسلمان) — PWA & Mobile Store Deployment

## GitHub Pages / Netlify
Upload `index.html`, `manifest.json`, and `sw.js` to any static host.

## PWABuilder / Capacitor (iOS, Android, Samsung Galaxy Store)
1. Host the static files on HTTPS (GitHub Pages or Netlify).
2. Run `npx @capacitor/cli init` or use PWABuilder (`https://www.pwabuilder.com/`) with your live HTTPS URL to generate signed Android `.aab/.apk`, iOS `.ipa`, and Samsung Galaxy Store packages.
