# Attraction Recode Website

Open `index.html` in a browser.

## Structure
- `index.html` — page content (nav, hero, mirror, method, process, pillars, about, testimonials, CTA, footer)
- `css/styles.css` — all layout and styling (dark plum/gold theme, Fraunces + Inter via Google Fonts)
- `js/main.js` — smooth scrolling for in-page nav links
- `images/tamara-original.jpg` — portrait used in the About section
- `images/tamara-profile.jpg`, `images/hero-extended.jpg`, `images/icon-*.svg` — unused by the current design, kept in case they're needed again

## Easy edits
- Booking links point to `https://calendly.com/tamarastupalova/coaching` — update in the hero, final CTA, and nav.
- Swap `images/tamara-original.jpg` for another photo using the same filename (crop ~4:5 works best; adjust framing via `.about-photo img{object-position}` in `css/styles.css`).
- Section anchors (`#method`, `#pillars`, `#about`, `#proof`, `#book`) drive both the nav and footer links — keep `id`s and hrefs in sync if you rename sections.
- Accent colors (`--gold`, `--rose`) and the base palette are defined as CSS variables at the top of `css/styles.css`.
