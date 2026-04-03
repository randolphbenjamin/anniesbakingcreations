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
- [ ] **Menu items** — Fill in all item names and prices for: Pies, Cookies, Kolaches, Dessert Platters, Seasonal Specials
- [ ] **Seasonal Specials** — This list should be updated regularly as offerings change
- [ ] **Easter Menu image** — Swap `ABC_Easter_Menu1_Testing.jpg` for the final version when ready; remove the seasonal callout block after Easter season ends

### Contact & Business Info
- [ ] **Full address** — Add complete street address in the Contact section
- [ ] **Phone number** — Add in Contact section

### FAQ Answers
- [ ] **Lead time** — How far in advance should orders be placed? (standard and custom)
- [ ] **Allergy/dietary policy** — What accommodations are available?

### Before Going Live
- [ ] **Remove noindex tag** — Delete the `<meta name="robots" content="noindex, nofollow">` line near the top of `<head>` in `index.html` to allow search engines to index the site
- [ ] **Activate order form** — Remove the `<div class="form-testing-banner">` block above the iframe and change the `form-shell` border from dashed amber back to `1px solid #FFE0E8`

---

## File Structure

```
anniesbakingcreations/
├── index.html                   ← entire site lives here
├── ABC_Logo.jpg                 ← logo (used in nav)
├── ABC_Homepage.jpg             ← hero background image
├── ABC_Stand_Retired.jpg        ← about section inset (retired farm stand)
├── ABC_Shop_Christmas_2025_1.jpg ← gallery
├── ABC_Shop_Christmas_2025_2.jpg ← about section main photo + gallery
├── ABC_Cake_1.jpg               ← gallery
├── ABC_Valentines_Group_1.jpg   ← gallery (featured tile)
├── ABC_StPatricks_Cookies_1.jpg ← gallery
├── ABC_Bunny_Bait_Close.jpg     ← gallery
├── ABC_Shelf_1.jpg              ← gallery
├── ABC_Strawberries.jpg         ← gallery
├── ABC_Easter_Menu1_Testing.jpg ← seasonal menu callout (draft)
├── CNAME                        ← GitHub Pages custom domain config
└── README.md                    ← this file
```

---

## Sections (in order)

1. **Hero** — Full-screen welcome with hero image + CTA
2. **About** — Annie's story, from farm stand to bake shop; shop as main photo, retired stand as inset
3. **Menu** — Easter seasonal callout + six categories: Pies, Cookies, Kolaches, Dessert Platters, Seasonal Specials, Custom Orders
4. **Custom Orders** — Spotlight section: weddings, birthdays, holidays, any occasion
5. **Gallery** — 8-tile responsive photo mosaic with real photos
6. **FAQ** — Native accordion, no JavaScript
7. **Order** — Google Form embed (live but in testing — do not submit real orders yet)
8. **Contact** — Location, phone, email, Facebook, Instagram
9. **Footer** — Copyright, nav links, social links, tagline
