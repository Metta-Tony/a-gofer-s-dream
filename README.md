# A Golfer’s Dream — Static 4-Page Site

This is a simple static 3-page site for a golf event: Home, Event Details & Registration (email-based), and Donate to Foundation (email-based). Betting content has been removed; any event-day wagering is handled at the venue if offered.

Files added:
- `index.html` — Home / hero / CTAs
- `event.html` — Event details, schedule, course info, registration instructions (mailto link)
- `donate.html` — Foundation donation options
- `styles.css` — Mobile-first CSS used by all pages

How to use:
1. Open any of the `.html` files in your browser (e.g., double-click `index.html`).
2. Replace placeholder images (e.g., course map) by adding files under `images/` and updating `src` in the HTML.
3. Replace example email addresses and external donation URL with real addresses/links.
4. Host as a static site (GitHub Pages, Netlify, Vercel, or your static host).

Notes & next steps:
Mailto links prefill subject/body for registration and pledges; these are intentionally simple (no backend required).
Replace the SVG background placeholder in `styles.css` with a course photo at `images/hero.jpg` for a better look.
If you want a contact form that sends emails without a backend, add a form-to-email provider (Formspree, Getform) and wire the form action accordingly.

License: you can reuse and adapt these templates for your event.
