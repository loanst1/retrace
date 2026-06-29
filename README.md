# retracerehab.com

Holding site for ReTrace — Ansteyapps cognitive rehabilitation app.

## Pages
- `index.html` — landing + early access
- `privacy-policy.html` — UK GDPR privacy policy (matches family naming)
- `terms-of-service.html` — terms of service (matches family naming)

## Deploying

This site is plain static HTML — no build step. Two recommended paths:

### Option A — Cloudflare Pages
1. Connect this repo in the Cloudflare dashboard
2. Build command: (leave empty)
3. Output dir: `/`
4. Add `retracerehab.com` as a custom domain

### Option B — GitHub Pages
1. Settings → Pages → Source: `main`, root
2. CNAME file is already in the repo
3. Point `retracerehab.com` A records to GitHub Pages IPs (or CNAME for `www`)

## Notes
- Same brand system as the other Ansteyapps sites (cream `#f5f1e8`, petrol `#2e5a6e`, Fraunces + Inter).
- Disclaimer present on every page: clinical adjunct, not a medical device.
- Contact emails: `hello@`, `clinical@`, `privacy@` `ansteyapps.com`.
