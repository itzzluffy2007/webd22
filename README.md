# webd22

# Task 22 — Tailwind Hero Landing Page

## Overview
This task implements a simple hero-style landing page built using Tailwind (via CDN) and Ionicons. The page showcases a header navigation, hero content, call-to-action buttons, and a few small status/info cards.

## Files
- index.html — main page (open in a browser to view the prototype)

## Features
- Responsive hero section with title, subtitle, and CTA buttons.
- Navigation bar with links and a primary action button.
- Decorative image loaded from an external URL.
- Small status/info cards positioned over the hero.
- Icons provided by Ionicons and Tailwind utilities via CDN.

## Dependencies
This project uses CDN-hosted assets (no local build required):
- Tailwind (browser build) — included in `index.html`:
  https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4
- Ionicons — included in `index.html` via unpkg (ESM and nomodule builds)

## How to view
1. Open [tutedude/task22/index.html](tutedude/task22/index.html) in your browser.
2. No build steps required — assets are loaded from CDNs.

## Notes & Customization
- To change the hero image, update the `src` attribute of the `<img>` tag in `index.html`.
- Tailwind utility classes are used directly in the markup; for larger projects consider using a proper Tailwind setup with a build step.
- Ionicons are loaded from unpkg; you can swap to a local copy or another icon set if preferred.

## License
You can reuse or adapt this example for learning and prototyping.

---

Created for Task 22 — generated README.
