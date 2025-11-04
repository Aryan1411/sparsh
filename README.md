# Dr. Sparsh Gupta — Portfolio Website

## Overview
A fast, responsive, single‑page portfolio website for Dr. Sparsh Gupta, MD (Medicine), Neurosurgeon. It highlights a professional overview, expertise, experience, testimonials, and contact options. This Round 2 update elevates the visual identity with a vibrant, dynamic color system while preserving speed, accessibility, and simplicity.

Key features:
- Vivid, multi‑stop animated gradient accents with 5 palette presets
- Light/Dark theme toggle with preference saved in localStorage
- Responsive layout for mobile, tablet, and desktop
- Accessible navigation, semantic structure, keyboard‑friendly controls
- Testimonials slider (auto + manual)
- Section reveal animations and smooth scrolling
- Contact form that composes an email locally (mailto — no backend needed)
- Downloadable vCard
- Print‑optimized summary
- SEO meta tags and JSON‑LD structured data (Physician)
- No external requests; fully self‑contained and fast

Tech stack: HTML5, CSS3, Vanilla JavaScript (no frameworks).

## Setup
No build tools are required.

- Option A: Open index.html in any modern browser.
- Option B: Serve locally for best results:
  - Python: python3 -m http.server 8080
  - Node: npx serve

This page has no external dependencies and should load well within 15 seconds even on slow connections.

## Usage
- Personalize contact details:
  - In index.html, replace dr.sparsh@example.com and +1‑000‑000‑0000 with real contact info.
- Navigation:
  - Header links scroll to sections. On mobile, use the menu button.
- Theme and colors:
  - Click the moon/sun icon to toggle light/dark theme.
  - Click the palette icon 🎨 to cycle between 5 vibrant accent palettes. Preferences are saved.
- Appointments:
  - Use the contact form to compose an email with your details (opens mail app).
  - Or click “Call Clinic.”
- vCard:
  - Click “Save vCard” to download a contact card you can import.
- Printing:
  - “Print Summary” produces a clean printout of key sections.

Content to personalize:
- Hero summary, clinical interests, services, and timeline details
- Add actual publications or a link to a CV file if available
- Update testimonials with verified quotes and permissions

## Improvements in Round 2
- Introduced a bold, vibrant color system:
  - Multi‑stop gradient accents (violet/cyan/amber by default) and four additional palettes
  - Gradient text headings, luminous chips, and animated conic logo
- Enhanced visual depth:
  - Subtle animated saturation on palette switch, soft glows, and colorful section separators
  - Glassy cards with gradient sheens and improved elevation/shadows
- Better usability and polish:
  - Stronger focus outlines with accent color
  - Accessible contrast in both light and dark modes
  - Sticky header with saturated blur and refined buttons
- Kept performance first:
  - Zero external assets, system fonts only, lightweight JS and CSS

## License (MIT)
Copyright (c) 2025 Sparsh Gupta

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.