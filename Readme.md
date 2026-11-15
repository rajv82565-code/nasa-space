# STILL HERE — ready-to-run website

A responsive, static-first interactive website based on the uploaded 17-page project brief for **Still Here**, Team RELICTRA@26, NASA Space Apps Challenge 2026.

## Run locally
1. Extract `still-here-website.zip`.
2. Open `index.html` in a modern browser.

For a local server (recommended):
- Python: `python -m http.server 8000`
- Visit `http://localhost:8000`

No build step, API key, sign-in, database, or framework installation is required.

## Included
- Responsive editorial-style landing page and three-world story trail.
- All 11 relics from the brief, with searchable/filterable cards and detailed story panels.
- Signal Status: Silent, Resting, Still Calling.
- Spirit vs Opportunity comparison.
- Three-question interactive quiz with feedback and score.
- Printable Mars teacher guide.
- Keyboard-friendly navigation, visible focus states, reduced-motion support, and mobile menu.

## Files
- `index.html` — page structure
- `styles.css` — visual system and responsive layout
- `script.js` — relic data and interactions

## Important content / launch notes
- The 11 relics and their story beats follow the supplied PDF. NASA links are included as starting references.
- The current build uses a designed orbital illustration rather than claiming that a decorative image is a real orbital photograph.
- The PDF describes before/after orbital imagery, 3D models and a live Voyager Signal Clock as planned experience features. Those are not represented as completed/live data in this static starter. Add verified NASA image assets with credits, compressed NASA 3D models, and a verified live telemetry source before presenting those capabilities as live.
- Verify all dates, counts, mission status and image credits against the cited NASA mission sources before public release. This is an educational concept and is not endorsed by NASA.

## Deploy
Upload the extracted folder to GitHub Pages, Netlify, Cloudflare Pages, or any static hosting provider. No environment variables are needed.
