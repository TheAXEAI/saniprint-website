# SaniPrint — saniprint.com

Static website for SaniPrint, a 3D printing factory in Pleven, Bulgaria.
Black & white editorial design system. No build step — pure HTML/CSS/JS, deployable on GitHub Pages.

## Pages
- `index.html` — homepage: hero (layer-by-layer print animation + typewriter), services, process, B2B, B2B order simulator, SaniCreate teaser
- `sanicreate.html` — SaniCreate: guided chat configurator with live monochrome preview and cost/ETA estimate
- `who-we-are.html`, `contact.html`, `terms.html`, `privacy.html`

## Notes
- All simulator/SaniCreate values are client-side estimates, clearly labeled as such
- `terms.html` and `privacy.html` are DRAFTS — review by a Bulgarian legal professional required before relying on them
- Placeholders marked with the `.placeholder` style must be filled with verified business details
- Fonts: Instrument Serif, Inter, JetBrains Mono (Google Fonts)
- Respects `prefers-reduced-motion`

## Deploy
Hosted on GitHub Pages. `CNAME` points the site at saniprint.com.
