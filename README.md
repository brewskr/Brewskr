# Brewskr Website — v3 (March 2026)

**Live:** https://brewskr.com  
**Netlify:** superlative-centaur-1b2dde.netlify.app

## What changed in this version
- Added "Why Now" editorial section (story + 4 stat cards) right after hero
- Added "Where It Happens" venue grid section (8 venue cards + Shoutout callout)
- "Why Now ↗" link added to nav and footer
- City dates updated: Abilene → 2026, Lubbock → 2026, Amarillo/DFW → Coming Soon
- Copyright updated to © 2026

## Page inventory

| File | URL | Notes |
|------|-----|-------|
| `index.html` | brewskr.com/ | Homepage |
| `why-now.html` | brewskr.com/why-now | Why Now editorial page |
| `privacy.html` | brewskr.com/privacy | Privacy Policy — NOT in this zip, already live |
| `terms.html` | brewskr.com/terms | Terms of Service — NOT in this zip, already live |
| `netlify.toml` | — | Routing + headers config |

## How to upload to GitHub (no command line needed)

1. Go to your Brewskr repo on **github.com**
2. Click **Add file → Upload files**
3. Drag in: `index.html`, `why-now.html`, `netlify.toml`
   - privacy.html and terms.html are already live — no need to re-upload unless you changed them
4. Add a commit note: *"Add venues section, Why Now section, update city dates"*
5. Click **Commit changes**
6. Netlify auto-deploys in ~30 seconds

## SEO — never change without a reason
- `<title>Brewskr — The Real-World Social App | Wichita Falls, TX</title>`
- `<link rel="canonical" href="https://brewskr.com/">`
- Google Search Console verification meta tag
- Section IDs: #hero #why #venues #how #features #tap #waitlist #cities #safety #pricing
