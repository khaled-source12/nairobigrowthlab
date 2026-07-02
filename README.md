# Nairobi Growth Lab — Website

Plain HTML/CSS site. No build step, no framework — works directly with GitHub + Vercel.

## Structure
```
index.html      → Home
services.html   → Services
work.html       → Work / case studies
about.html      → About / team
contact.html    → Contact
assets/css/style.css   → All styling + brand tokens (colors, fonts)
assets/js/main.js      → Mobile menu toggle
assets/images/logo.png → Logo
```

## Deploy on Vercel
1. Push this folder to a GitHub repo.
2. In Vercel: New Project → Import the repo → Framework preset: "Other" → Deploy.
   No build command needed, it's static HTML.
3. Every push to the connected branch auto-redeploys.

## Editing with Claude
Paste the relevant .html file (or assets/css/style.css for site-wide style changes)
into a chat and describe the edit. Colors/fonts are defined once at the top of
style.css as CSS variables (--lab-green, --amber, --ink, etc.) — change them there
to restyle the whole site at once.

## Known placeholders to replace before launch
- Team photos (About page) — currently initials placeholders, swap in real photos
- Team bios (About page) — drafted from public info, have each person review/edit
- Contact form — not yet connected to an email service (e.g. Formspree, Web3Forms)
- WhatsApp number in contact.html (currently a placeholder wa.me link)
- Email address hello@nairobigrowthlab.com — set up or replace with real inbox
- TikTok link — the TikTok URL provided matched the Instagram URL exactly,
  so it's currently pointing to Instagram in both places. Send the real TikTok
  link and it's a one-line fix in each HTML file's footer/header.
- Case studies (Work page) — placeholder cards, fill in once pilot results exist
