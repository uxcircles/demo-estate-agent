# Alder & Wren — design demo

> **Fictional agency.** A design demo by [UX CIRCLES](https://ux-circles.com/professionals). Alder & Wren is not a real business, the listings are invented, and nothing on this site is property, legal or tax advice. Membership numbers are placeholders.

A four-language website (English · 繁體中文 · 廣東話 written Cantonese · 简体中文) for a London estate agent serving Taiwanese and Hong Kong buyers and tenants.

- `/` English · `/zh-hant/` Traditional Chinese · `/yue/` Cantonese · `/zh-hans/` Simplified Chinese, linked with `hreflang` (the Cantonese page uses `lang="yue-Hant-HK"` and `hreflang="zh-HK"`, since Google does not support `yue` in hreflang)
- Listings with material information up front (tenure, council tax band, EPC, deposit)
- Area guides and a step-by-step buying guide for new arrivals
- Photos from Pexels (free to use under the Pexels License): [hero](https://www.pexels.com/photo/bench-under-sash-window-of-a-navy-blue-brick-house-surrounded-by-ivy-19128683/), [listings](https://www.pexels.com/photo/terraced-houses-in-london-20703515/) and similar London street and apartment photos. Listing photos are illustrative only.
- `RealEstateAgent`, `Person` and `FAQPage` structured data
- Plain HTML, CSS and JavaScript — no build step. Pages are `noindex` so the fictional agency does not appear in search results.

Live demo: https://uxcircles.github.io/demo-estate-agent/
