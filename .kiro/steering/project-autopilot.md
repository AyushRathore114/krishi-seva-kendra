---
inclusion: always
---

# Project Autopilot — श्री नारायण कृषि सेवा केंद्र

Continuously improve a single-file, mobile-first Hindi agricultural shop website
at /projects/sandbox/index.html.

## Rules
- Keep everything in ONE index.html (HTML + CSS + vanilla JS, CDN libs only, no backend).
- Hindi-first (Devanagari), farmer-friendly, low-data, Android-friendly.
- Never remove working features; only enhance or replace with something better.
- Keep all owner-editable data in JS objects/arrays at the top of the script.
- Keep placeholder business values (WEBSITE_URL, SHOP_PHONE, etc.) intact.
- After each change: verify the HTML is valid, no JS console errors, mobile layout holds.
- Escape all dynamic strings before injecting into the DOM (prevent XSS).
- Respect prefers-reduced-motion for all animations.
- Ensure focus-visible styles on all interactive elements.

## Iterative Testing Mandate
For every feature/aspect: test from different angles (mobile, offline, dark mode,
slow network, accessibility, admin-edited data), fix the root cause of each failure,
then re-verify. Never skip a failure.
