# QA — Фризьорски салон TEDY

- Gate 1 source/fact audit: PASS — business name, category, phone, address, Facebook, Google Maps CID/place, hours, services, testimonials, and selected images recorded in `image-map.md`. No invented prices, credentials, awards, review counts, or guarantees in customer-facing copy.
- Gate 2 visual-result image audit: PASS — public gallery images from Infobusiness/Facebook presence inspected; selected 6 crop-safe hair/result images; rejected cluttered/duplicate/weak images. Real result images used in hero and gallery.
- Gate 3 testimonial audit: PASS — written client reviews with real displayed names taken from Titul mirror page; original Bulgarian/Latin names and original review wording preserved; no rating-only or anonymous testimonial cards.
- Gate 4 copy audit: PASS — customer-facing text inspected; H1 clearly states profession + location + service/result; removed source/meta explanations; no placeholders/TODO/Lorem/dynamic review counts.
- Gate 5 link/schema audit: PASS — phone, Facebook, Google Maps, nav anchors, canonical, and HairSalon schema present. Opening hours included as verified from Titul.
- Gate 6 image/layout audit: PASS — all image assets load; no duplicate file use; hero not reused in gallery; portrait frames match portrait sources; no letterboxing, visible card container frames, or awkward hair-result crop in final screenshots.
- Gate 7 map/local SEO audit: PASS — bottom map/contact block directly above footer; embedded Google Maps iframe has explicit width/height, visibly loads in focused QA, fills the designed map container; exactly one visible navigation CTA in contact block.
- Gate 8 responsive visual QA: PASS — desktop/mobile screenshots inspected by strict image QA after fixes; no blockers for typography, image crop, gallery, testimonials, map, footer icons, mobile rhythm, or CTA duplication. Footer links use polished high-contrast SVG icon buttons, not raw letter badges or low-contrast glyphs.
- Gate 9 final live QA: PASS — GitHub Pages HTTP 200; live screenshots passed strict desktop/mobile visual QA; live HTML contains business name, testimonial phrase, and embedded Google Maps iframe.

## Notes
- Address conflict documented in `image-map.md`; site uses Google Places/Titul address `бул. Ломско шосе 57, ж.к. Надежда 1`, matching row/CID.
- Final local screenshots: `artifacts/tedi-desktop-final2.png`, `artifacts/tedi-mobile-final2.png`.
