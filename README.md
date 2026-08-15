# Grün & Grund – Website-Mockup (Demo)

Single-file design mockup for a garden & property maintenance business in the
Ulm region (Germany). Built as a static HTML/CSS/JS prototype; the production
site will be rebuilt in Angular and hosted on Cloudflare Pages.

**Live demo:** via GitHub Pages (see repository settings / About).

## Status: mockup, not production

- All contact data (phone, e-mail, address) is placeholder dummy data.
- Company name/wordmark "Grün & Grund" is a working placeholder.
- Photos are temporary stock stand-ins; the final site will use real photos of
  completed work only.
- Fonts load from Google Fonts **for preview only** — the production build must
  self-host them (GDPR, see comment in `index.html`).
- German copy pending native-speaker review.

## Features

- Two color schemes (Forest / Premium) via CSS custom properties
- DE/EN language switch (DOM-based i18n dictionary)
- Two-click GDPR-compliant Google Maps embed
- Scroll-reveal animations with `prefers-reduced-motion` support
- Responsive: 360px → desktop, keyboard-accessible carousel and speed-dial
