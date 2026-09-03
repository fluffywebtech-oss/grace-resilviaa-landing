# Grace Resilviaa — Landing Page

Standalone marketing landing page for **Grace Resilviaa** — 3-BHK residential apartments in Sector 78, Gurugram ("Graceful Living, Resilient Foundations", an undertaking of Hercules Ventures LLP).

Independent static project (HTML/CSS/JS), no build step, no dependency on any other project. All imagery is sourced from the provided reference asset folder and optimized to WebP.

## Structure
```
grace-resilviaa-landing/
├── index.html   # all sections
├── styles.css   # green & gold design system (warm, rounded)
├── script.js    # sticky nav, mobile menu, scroll-reveal, gallery lightbox, enquiry form
└── assets/       # WebP images (hero banner, clubhouse, pool, yoga, plans, master/location maps)
```

## Run
```bash
cd grace-resilviaa-landing && python3 -m http.server 5600
```
Open http://localhost:5600

## Sections
Hero · About/Highlights (6 features) · Plans · Amenities · Gallery · Location · Blog · Contact · Footer

## Notes
- RERA: RC/REP/HARERA/GGM/957/689/2025/60 · haryanarera.gov.in
- Images are artist's impressions; actual may vary.
- The enquiry form is front-end only — wire it to your CRM/endpoint before going live.
