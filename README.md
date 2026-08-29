# WeddingPage
ibrahim-khadijah-wedding 2026

## Edit first
Open `data.js`. Change:
- couple names
- wedding date
- city and venue
- programme and reception text
- colour code
- story
- RSVP contacts
- registry categories/items
- FAQ

## Pages
- `index.html` — landing page, story, event, registry categories, gallery, RSVP, FAQ
- `registry.html` — gift catalogue, filter, display currency, demo basket
- `gallery.html` — photo gallery

## Styling
Edit the variables at the top of `styles.css` to change the main theme colours.

## RSVP
The RSVP form opens a pre-filled WhatsApp message to the first RSVP contact in `data.js`.

## Payments
The registry is intentionally demo-only. Do not collect card or bank credentials in this static template. For production, connect a secure provider such as Stripe, Paystack or Flutterwave through a proper backend/serverless function.

## Preview
Open `index.html` in a browser, or run:
`python3 -m http.server 8000`

## Hosting
Works as a static site on Netlify, Vercel, Cloudflare Pages or GitHub Pages.
