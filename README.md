# Dr. Sparsh Gupta — Portfolio Website

## Overview
This is a fast, responsive, single‑page portfolio website for Dr. Sparsh Gupta, MD (Medicine), Neurosurgeon with 5 years of clinical experience. It highlights professional overview, expertise, experience, testimonials, and contact options.

Key features:
- Responsive layout for mobile, tablet, and desktop
- Accessible navigation, semantic structure, and keyboard‑friendly controls
- Light/Dark theme toggle with preference remembered
- Lightweight assets (no external requests) for fast load
- Testimonials slider, section reveal animations, and smooth scrolling
- Contact form that composes an email locally (no backend required)
- Downloadable vCard
- SEO meta tags and JSON‑LD structured data (Physician)

Tech stack: HTML5, CSS3, Vanilla JavaScript (no frameworks).

## Setup
No build tools are required.

- Option A: Open index.html in any modern browser.
- Option B: Serve locally for best results:
  - Python: python3 -m http.server 8080
  - Node: npx serve

The page has no external dependencies and should load well within 15 seconds even on slow connections.

## Usage
- Customize contact details:
  - In index.html, search for dr.sparsh@example.com and +1‑000‑000‑0000 and replace with real contact info.
- Navigation:
  - Header links scroll to sections. On mobile, use the menu button.
- Theme:
  - Click the moon/sun icon to toggle. Preference is saved in localStorage.
- Appointments:
  - Click “Book Appointment,” “Call Clinic,” or use the contact form to compose an email with your details.
- vCard:
  - “Save vCard” downloads a contact card you can import into your address book.
- Printing:
  - “Print Summary” produces a clean printout of key sections.

Content to personalize:
- Hero summary, clinical interests, services, and timeline details
- Add actual publications or a link to a CV file if available
- Update testimonials with verified quotes and permissions

## License (MIT)
Copyright (c) 2025 Sparsh Gupta

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.