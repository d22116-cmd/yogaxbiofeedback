# Dhyanly™ — Intelligent Wellness Suite

**by YogaXBiofeedback Private Limited**  
CIN: U62011DL2026PTC462641 · Trademark Applied · April 2026

---

## Overview

Dhyanly™ is a suite of AI-powered wellness applications rooted in Indian Knowledge Systems (IKS) and validated by clinical neuroscience. Built at IIT Mandi's IKSMHA Centre for Consciousness Studies.

---

## Suite

| File | App | Status |
|------|-----|--------|
| `index.html` | Dhyanly™ Brand Hub | ✅ Live |
| `mcas.html` | MCAS — Mindful Content Awareness System | ✅ Live |
| `dhyanly-app.html` | DhyanlyApp — Mental Health Monitor | ✅ Live |
| `svara-flow.html` | SvaraFlow — Yoga, Habit & Journal Studio | ✅ Live |
| `yoga-arena.html` | YogaArena — Body Intelligence Game Engine | ✅ Live |

---

## Architecture

Each app is a self-contained single HTML file. The main `index.html` acts as the brand hub and links to each module. To add or update a module, replace its file — no changes to `index.html` needed.

```
dhyanly/
├── index.html
├── mcas.html
├── dhyanly-app.html
├── svara-flow.html
├── yoga-arena.html
├── 404.html
├── favicon.svg
├── robots.txt
├── sitemap.xml
└── README.md
```

---

## Deploy to GitHub Pages

1. Create a new **public** GitHub repository
2. Upload all files to the root
3. Go to **Settings → Pages → Deploy from branch → main → / (root)**
4. Site goes live at `https://yourusername.github.io/repo-name`

**Custom domain:** add a `CNAME` file with your domain, configure DNS CNAME to `yourusername.github.io`

---

## Technology

- Pure HTML5 / CSS3 / JavaScript — zero dependencies, zero build step
- Fonts: Google Fonts (Fraunces, Plus Jakarta Sans, Azeret Mono)
- MediaPipe PoseNet for skeletal detection (YogaArena)
- Canvas API for all data visualisations
- 100% on-device — no backend, no database, no user data transmitted

---

**Contact:** satyam@yogaxbiofeedback.com  
© 2026 YogaXBiofeedback Private Limited. All rights reserved.
