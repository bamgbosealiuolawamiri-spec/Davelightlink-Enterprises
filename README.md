# Davelightlink Oil & Gas Website

Responsive static website with a white background and blue navigation. Sections include Home, Services, Book a Service, About, Gallery and Contact.

## Files
- `index.html` — page content and navigation
- `styles.css` — responsive styling
- `script.js` — mobile navigation and enquiry form

## Before publishing
1. Confirm all listed services accurately reflect the company's real capabilities.
2. Add the verified company email in `script.js` by replacing the empty `businessEmail` value.
3. Add the real company phone number, address and authorised project photographs.
4. The booking form currently downloads a text file. It does not store enquiries on a server. Configure a verified email or form backend before relying on it.
5. The gallery contains CSS illustrations, not real company project photographs.

## Cloudflare Pages deployment
Use Cloudflare Dashboard → Workers & Pages → Create → Pages (or the current static-site upload option). Upload the website files with `index.html` at the root. Do not edit or replace any other project such as PricePulse World.
