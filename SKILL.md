---
name: daqing-strategy-guide
description: Maintain and extend the Vite-based Thai interactive business strategy guide while preserving its content and existing interactions.
---

# Da Qing Strategy Guide

Use this guide when working on this repository's web page.

## Project Facts
- The app is a single-page Vite site with `index.html` as its entry point.
- The original source is `พ่อค้าแห่งต้าชิง.html`; treat it as a reference and do not overwrite it unless explicitly requested.
- The page currently uses Tailwind CSS, Alpine.js, and Google Fonts from external CDNs.
- Existing interactions include search, category filtering, bookmarks stored in local storage, a strategy detail modal, clipboard copy, and text report export.

## Workflow
1. Read the relevant section of `index.html` before changing the page.
2. Keep existing Thai copy and interactions intact unless the requested change calls for a behavior change.
3. Keep the implementation within the current Vite and single-page setup unless a task explicitly asks for a larger architectural change.
4. Run `npm run build` after application changes and report any checks that could not be run.
5. Update `README.md` if setup steps or project commands change.
