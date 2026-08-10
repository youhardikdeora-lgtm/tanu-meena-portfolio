# Change log

## 2026-08-10 — production-readiness refinement

| File | Change | Reason and expected benefit |
| --- | --- | --- |
| `index.html` | Added semantic page landmarks, a skip link, mobile section navigation, responsive-grid safeguards, and reduced-motion handling. | Improves keyboard access and keeps the portfolio usable from 320px upward. |
| `index.html` | Reworked modal behavior to manage focus, trap keyboard navigation, restore the invoking control, and make background content inert. | Brings dialogs in line with modern keyboard and screen-reader expectations. |
| `index.html` | Persisted the chosen colour theme, improved image loading metadata, and added a direct telephone link. | Makes the experience more consistent and responsive. |
| `index.html` | Replaced missing CV downloads with a CV request link; removed unsupported performance claims and broken project URLs. | Prevents dead ends and keeps portfolio claims supportable by the linked project evidence. |
| `index.html`, `robots.txt`, `sitemap.xml` | Added canonical, social metadata, JSON-LD Person data, crawl directives, and a sitemap. | Improves discoverability and social sharing readiness. |
| `assets/favicon.svg` | Added a lightweight local monogram favicon. | Removes the prior missing favicon request. |
