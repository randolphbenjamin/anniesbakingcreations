# Annie's Baking Creations — Website

Single-page website for **Annie's Baking Creations**, Bassett, WI.
Built as a single `index.html` file with inline CSS and no JavaScript frameworks.

---

## Tech Stack

- Plain HTML5 + inline CSS (no external stylesheets, no JS frameworks)
- Google Fonts: Dancing Script · Playfair Display · Lato
- CSS-only mobile nav (checkbox hack, no JavaScript)
- Native `<details>`/`<summary>` for the FAQ accordion

---

## Open TODOs

All items below are also marked with `<!-- TODO: -->` comments directly in `index.html`.

### Content
- [ ] **Tagline** — Update hero tagline with Annie's preferred wording
- [ ] **About copy** — Write full "Our Story" section text
- [ ] **About photo** — Replace placeholder `<div>` in About section with a real photo of Annie / the shop
- [ ] **Menu items** — Fill in all item names and prices for: Pies, Cookies, Kolaches, Dessert Platters, Seasonal Specials
- [ ] **Seasonal Specials** — This list should be updated regularly as offerings change

### Contact & Business Info
- [ ] **Full address** — Add complete street address in the Contact section and footer
- [ ] **Phone number** — Add in Contact section
- [ ] **Facebook URL** — Add to Contact section and footer social links
- [ ] **Instagram URL** — Add to Contact section and footer social links

### FAQ Answers
- [ ] **Lead time** — How far in advance should orders be placed? (standard and custom)
- [ ] **Allergy/dietary policy** — What accommodations are available?

### Before Going Live
- [ ] **Remove noindex tag** — Delete (or change to `index, follow`) the `<meta name="robots" content="noindex, nofollow">` line near the top of `<head>` in `index.html`. This tag is intentionally blocking search engines while the site is under construction. Removing it allows Google and other search engines to index the site.

### Functionality
- [ ] **Google Form** — Embed order form in the Order section:
  1. Open your Google Form
  2. Click Send → Embed icon (`<>`)
  3. Copy the iframe `src` URL
  4. Replace the placeholder `<div class="form-shell">` block with:
     ```html
     <iframe
       src="YOUR_GOOGLE_FORM_EMBED_URL_HERE"
       width="100%"
       height="700"
       frameborder="0"
       style="border:none;border-radius:22px;"
       title="Order Form">
     </iframe>
     ```

### Gallery
- [ ] **Photos** — Replace all 8 `<div class="gallery-item">` placeholder tiles with real `<img>` tags.
  Suggested format per tile:
  ```html
  <div class="gallery-item">
    <img src="photo-name.jpg" alt="Description" style="width:100%;height:100%;object-fit:cover;">
  </div>
  ```

---

## File Structure

```
anniesbakingcreations/
├── index.html       ← entire site lives here
├── ABC_Logo.jpg     ← logo (used in nav)
├── ABC_Homepage.jpg ← hero background image
├── CNAME            ← GitHub Pages custom domain config
└── README.md        ← this file
```

---

## Sections (in order)

1. **Hero** — Full-screen welcome with hero image + CTA
2. **About** — Annie's story, from farm stand to bake shop
3. **Menu** — Six categories: Pies, Cookies, Kolaches, Dessert Platters, Seasonal Specials, Custom Orders
4. **Custom Orders** — Spotlight section: weddings, birthdays, holidays, any occasion
5. **Gallery** — 8-tile responsive photo mosaic
6. **FAQ** — Native accordion, no JavaScript
7. **Order** — Google Form embed
8. **Contact** — Location, phone, email, social links
9. **Footer** — Copyright, nav links, social links, tagline
