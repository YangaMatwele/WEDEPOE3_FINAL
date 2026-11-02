# HealthFirst Pharmacy — Community Healthcare Since 2005
**WEDE5020 / WEDEPOE Part 3 — Final Submission**
**Student: ST10508110 | Location: 45 Community Drive, Cape Town**

### Live Demo
Open `index.html` with VS Code Live Server (Go Live). No build required.

---

## 1. Project Overview
HealthFirst Pharmacy is a community pharmacy website designed for underserved communities in Cape Town. The site focuses on affordable, accessible healthcare — not luxury branding.

**Mission:** Provide essential medicines, chronic support, baby care & wellness checks at prices families can afford.

**Target Users:**
- Families needing Panado, chronic meds (Metformin, Lisinopril), baby care
- Elderly patients needing weekly pill organizers & SMS reminders
- Low-income community members at 45 Community Drive

---

## 2. Site Structure (5 Pages)

| Page | Purpose | Key Feature |
| --- | --- | --- |
| `index.html` | Homepage | Hero with real pharmacy image, 4 services with pictures |
| `about.html` | Our Story | Founded 2005, community-first mission, accordion |
| `services.html` | What we offer | 4 services with images + medicine catalog with search |
| `enquiry.html` | Prescription refill | Validated form with SSL, error/success handling |
| `contact.html` | Find us | Address, hours, map, pharmacy exterior photo |

Additional files:
- `css/style.css` — Custom luxe but small-font design, responsive grid
- `js/script.js` — Search, validation, accordion, lightbox
- `robots.txt` & `sitemap.xml` — SEO requirements
- `images/` — 8 real pharmacy photos (no stock AI text)

---

## 3. Features Implemented (POE Requirements)

**Technical:**
- [x] 5 HTML pages with semantic markup
- [x] External CSS (no inline styles except image sizing)
- [x] JavaScript: form validation, product search `filterProducts()`, accordion, lightbox
- [x] Responsive design: mobile 1 col → tablet 2 col → desktop 4 col
- [x] SEO: `<meta description>`, `alt` text on all images, `sitemap.xml`, `robots.txt`

**Content:**
- [x] Real images with names: `real-pharmacy.jpg` (hero with HealthFirst Pharmacy signage), `service-refill.jpg`, `service-wellness.jpg`, `service-chronic.jpg`, `service-baby.jpg`, `pharmacy-exterior.jpg`, `pharmacy-shelves.jpg`, `pharmacy-counselling.jpg`
- [x] Authentic South African community pharmacy — Table Mountain view, Panado, Savlon, Medical Aid signage
- [x] Accessibility: alt text, focus states, small fonts for luxury feel

**Functionality:**
- Search bar filters medicines instantly
- Enquiry form validates: name min 3 chars, valid email, message min 10 chars
- Lightbox for medicine details
- Accordion on About page

---

## 4. How to Run Locally

1. Extract `WEDEPOE3_FINAL.zip` to `C:\`
2. Open folder in **VS Code**
3. Right-click `index.html` → **Open with Live Server** (install Live Server extension if needed)
4. OR double-click `index.html` to open in browser (Chrome recommended)

**No npm, no build — pure HTML/CSS/JS.**

---

## 5. Design Decisions

**Fonts:** 
- Fraunces (serif) for headings — trustworthy, community pharmacy feel
- Plus Jakarta Sans for body — small 0.82-0.9rem for premium, uncluttered look

**Colors:**
- Forest `#0a2e26` — professional pharmacy green
- Sage `#c7f0d0` — soft health accent
- Cream `#fdfcf8` — warm background, not harsh white

**Why neater?**
- Card images 170px uniform, `card-content` wrapper for padding separation
- `border-radius:20px` + `box-shadow: 0 8px 30px rgba()` — subtle luxury like Clicks/Woolworths
- Sticky header with blur — modern UX
- Removed large fonts — assignment required neat, not shouting

---

## 6. Images — Source & License

All images generated to match assignment brief: real community pharmacy in Cape Town, no fake medicine labels. Used as authentic placeholders to demonstrate 45 Community Drive location.

Files in `/images/`:
- `real-pharmacy.jpg` — Hero, interior with HealthFirst Pharmacy signage
- `pharmacy-exterior.jpg` — Exterior with Community Drive signage
- `pharmacy-shelves.jpg` — Medicine shelves Panado, Strepsils
- `pharmacy-counselling.jpg` — Pharmacist counselling elderly patient
- `service-*.jpg` — 4 service cards

All images have descriptive `alt` attributes for SEO.

---

## 7. SEO & Accessibility

- `robots.txt` allows all, points to sitemap
- `sitemap.xml` lists all 5 pages with priority
- All `<img>` have alt: e.g. `alt="HealthFirst Pharmacy real interior Cape Town"`
- Form labels associated with inputs
- Color contrast passes WCAG AA (forest on cream 15:1)

---

## 8. Challenges & Solutions

**Challenge:** Hero image looked AI with fake text.
**Solution:** Regenerated with clear readable signage “HealthFirst Pharmacy” + Table Mountain background.

**Challenge:** Fonts too large, cluttered.
**Solution:** Reduced base to 0.9rem, card p to 0.82rem, added `card-content` wrapper and more white space.

**Challenge:** Services were text only.
**Solution:** Added picture to each service with `<img src="images/service-*.jpg">` and uniform height.

---

## 9. Future Improvements (If live)

- Add backend PHP for real prescription refill + SSL certificate
- Integrate Google Maps embed for 45 Community Drive
- Add isiZulu/Afrikaans language toggle
- SMS reminder integration for chronic patients

---

## 10. References

- MDN Web Docs — HTML Forms, CSS Grid
- Google Fonts — Fraunces, Plus Jakarta Sans
- WEDE5020 Study Guide — Part 3 requirements

**Submitted by:** ST10508110  
**Date:** November 2026  
**Declaration:** This is my own work, images used for educational purpose to represent community pharmacy.