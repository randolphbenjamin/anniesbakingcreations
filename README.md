# Annie's Baking Creations — Website

Single-page website for **Annie's Baking Creations**, Bassett, WI.
Built as a single `index.html` file with inline CSS and no JavaScript frameworks.

---

## Tech Stack

- Plain HTML5 + inline CSS (no external stylesheets, no JS frameworks)
- Google Fonts: Dancing Script · Playfair Display · Lato
- CSS-only mobile nav (checkbox hack, no JavaScript)
- Native `<details>`/`<summary>` for the FAQ accordion
- Live menu data fetched from Google Sheets (no backend required)
- Contact info (phone/email) injected via JS with base64 encoding to deter scrapers

---

## Open TODOs

### Seasonal
- [ ] **Seasonal callout** — Uncomment the seasonal feature block in the Menu section for the next holiday; update the 5 labeled fields (image, eyebrow, heading, description, button text)

---

## File Structure

```
anniesbakingcreations/
├── index.html                    ← entire site lives here
├── ABC_Logo.jpg                  ← logo (used in nav)
├── ABC_Homepage.jpg              ← hero background image
├── ABC_Stand_Retired.jpg         ← about section inset (retired farm stand)
├── ABC_Shop_Christmas_2025_1.jpg ← gallery
├── ABC_Shop_Christmas_2025_2.jpg ← about section main photo + gallery
├── ABC_Cake_1.jpg                ← gallery
├── ABC_Valentines_Group_1.jpg    ← gallery (featured tile, spans 2×2)
├── ABC_StPatricks_Cookies_1.jpg  ← gallery
├── ABC_Bunny_Bait_Close.jpg      ← gallery
├── ABC_Shelf_1.jpg               ← gallery
├── ABC_Croissant.jpeg            ← gallery (wide tile, spans 2 cols)
├── ABC_Flower_Cookies.jpeg       ← gallery
├── ABC_Flower_Cookies_2.jpeg     ← gallery
├── ABC_Red_Velvet_Cake.jpeg      ← gallery
├── ABC_Red_Velvet_Cupcake.jpeg   ← gallery
├── ABC_Easter_Menu1_Testing.jpg  ← seasonal callout image (currently commented out)
├── ABC_Strawberries.jpg          ← unused (replaced by new jpeg tiles)
├── CNAME                         ← GitHub Pages custom domain config
└── README.md                     ← this file
```

---

## Sections (in order)

1. **Hero** — Full-screen welcome with hero image + CTA
2. **About** — Annie's story, from farm stand to bake shop; shop as main photo, retired stand as inset
3. **Menu** — Seasonal callout (commented out, reusable) + live tabs from Google Sheets
4. **Custom Orders** — Spotlight section: weddings, birthdays, holidays, any occasion
5. **Gallery** — 12-tile responsive photo mosaic
6. **FAQ** — Native accordion, no JavaScript
7. **Order** — Google Form embed (live)
8. **Contact** — Location + Google Maps link, phone, email, Facebook, Instagram
9. **Footer** — Copyright, nav links, social links, tagline
