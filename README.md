# Texas Garage and Gate — Website

A modern, responsive marketing site for **Texas Garage and Gate**, a garage door and
gate service business in San Marcos, TX.

> **Status:** Demo concept build. Built to showcase the design direction and to
> demonstrate how real job photography would elevate the site.

## Business

- **Texas Garage and Gate** — garage door & gate sales, repair, and installation
- 206 N Guadalupe St, San Marcos, TX 78666
- (512) 661-5364 · Open 24 hours

## Stack

Plain, dependency-free static site — fast to host anywhere (GitHub Pages, Netlify, etc.).

- `index.html` — single-page layout (hero, services, why-us, gallery, service area, contact)
- `css/styles.css` — all styling, responsive down to mobile
- `js/main.js` — mobile nav toggle + footer year
- `images/` — site imagery

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## To-do before launch

- [ ] Add real job photos to the "Our Work" gallery (placeholder slots are marked)
- [ ] Connect the contact form to a real backend (currently a `mailto:` demo)
- [ ] Replace the demo banner / demo tag once approved
