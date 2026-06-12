# Torii × Technical Hub — Claude AI Success Story Website

A responsive, single-page success-story website built with the **same technology stack as
[toriiminds.com](https://toriiminds.com/)** — a fast, framework-free **static HTML + CSS + vanilla
JavaScript** site (no build step, no dependencies). It presents the case study *"How Technical Hub
Upskilled Torii to Deliver Industry-Standard Claude AI Training & Engineering."*

## Project structure

```
Technical_Hub_Torii_Claude_Success_Story/
├── index.html                 # All page sections
├── css/
│   └── styles.css             # Brand palette, layout, responsive rules
├── js/
│   └── main.js                # Mobile nav, scroll-reveal, animated counters
├── assets/
│   ├── torii-logo.png         # Official Torii logo (trimmed, transparent)
│   ├── technical-hub-logo.png # Official Technical Hub logo
│   ├── team-photo.jpg         # Official Torii delivery-team photo
│   └── training-classroom.jpg # Official developer-training photo
└── README.md
```

## How to run

It's a static site — just open it. No install required.

- **Quickest:** double-click `index.html`.
- **Recommended (so relative paths/fonts behave like production):** serve locally —
  - Python: `python -m http.server 8000` then visit `http://localhost:8000`
  - VS Code: right-click `index.html` → *Open with Live Server*.

## Page sections

1. **Hero** — headline, partner card, key meta (Partner / Client / Focus).
2. **Stats strip** — animated outcome counters.
3. **Executive Summary** — overview from the PDF.
4. **Trainer Readiness** — train-the-trainer framework + checklist (team photo).
5. **Engineering Velocity** — developer tracks + three capability cards
   (Context-Aware Code Assistance, Automated QA, Accelerated Prototyping).
6. **Measurable Impact** — four KPI cards.
7. **The Journey** — 4-step timeline (added/recommended content).
8. **Conclusion / CTA** — closing statement + contact buttons.
9. **Footer** — navigation, partnership links, dual branding.

All wording is taken from the supplied PDF; the stats strip, timeline, and impact cards are
recommended additions that visualise the case study.

## Images & logos

All artwork is the **genuine source material**, extracted from the original
`Technical_Hub_Torii_Claude_Success_Story` document and wired directly into the page:

| Asset                          | File                             | Used in              |
|--------------------------------|----------------------------------|----------------------|
| Torii logo (transparent PNG)   | `assets/torii-logo.png`          | Header & footer      |
| Technical Hub logo             | `assets/technical-hub-logo.png`  | Hero card & footer   |
| Torii delivery-team photo      | `assets/team-photo.jpg`          | Trainer Readiness    |
| Developer-training session     | `assets/training-classroom.jpg`  | Engineering Velocity |

The Torii logo's surrounding whitespace was trimmed to a tight bounding box so it sits cleanly in
the header. To swap any image, just replace the file in `assets/` keeping the same name.

## Brand palette

| Token   | Hex       | Use                         |
|---------|-----------|-----------------------------|
| Orange  | `#f26522` | Torii accent / primary CTA  |
| Navy    | `#1f3864` | Headings (matches the PDF)  |
| Green   | `#76bc21` / `#3f9b1f` | Technical Hub accents |

Fonts: **Poppins** (headings) + **Inter** (body), loaded from Google Fonts.

## Customising

- Colours and spacing live as CSS variables at the top of `css/styles.css` (`:root`).
- Copy lives directly in `index.html`.
- Contact email/links point to `support@toriiminds.com` and `toriiminds.com` — update in the
  CTA and footer as needed.
