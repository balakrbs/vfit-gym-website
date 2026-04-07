# VFIT GYM — No Excuses. Just Results.

![VFIT Gym](https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=1200&q=80&fit=crop)

> **Live Site → [vfitmatrix-gym.netlify.app](https://vfitmatrix-gym.netlify.app/)**

A modern, raw, high-impact gym website built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies. Designed to feel like a real transformation-focused training zone, not a commercial template.

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `vfit-gym-landing.html` | Hero, philosophy, stats, coaches, programs, membership, gallery, CTA |
| About | `about.html` | Origin story, core values, milestone timeline |
| Programs | `programs.html` | 4 programs with tab switcher, phase breakdowns, results |
| Coaches | `coaches.html` | Head coach feature + 6 coach cards with hover-reveal |
| Gallery | `gallery.html` | Masonry grid, category filter, lightbox with keyboard nav |
| Contact | `contact.html` | Enquiry form, hours, Google Maps embed, free trial CTA |
| Blog | `blog.html` | 7 articles, category filter, full in-page article reader |

---

## Design System

```
Primary Color   →  #FF4D00  (energy, power, intensity)
Background      →  #0a0a0a / #111111 (deep black / charcoal)
Text            →  #f0ede8 (warm white)
Accent          →  #888888 (muted grey)
Border          →  #222222

Display Font    →  Bebas Neue
UI Font         →  Barlow Condensed
Body Font       →  Barlow
```

**Design Philosophy:**
- Industrial dark UI — raw, not polished
- `#FF4D00` used only for CTAs, highlights, and progress indicators
- Grain texture overlay for gritty industrial feel
- Bold Bebas Neue typography for maximum impact
- No over-designed sections — overlapping blocks, broken grid layout

---

## Features

- Scroll progress bar (orange, top edge)
- Sticky navbar with scroll-triggered background
- Scroll-reveal animations (fade + slide) on all sections
- Animated stat counters (fire on scroll)
- Before/After drag slider (Stats section)
- Program tab switcher (Programs page)
- Masonry gallery grid with category filter
- Lightbox with keyboard navigation (← → Esc)
- In-page article reader (Blog page)
- Contact form with success state
- Google Maps embed (Contact page)
- Grain/noise texture overlay (body::before)
- Fully responsive — mobile-first friendly
- Zero dependencies — pure HTML/CSS/JS

---

## Project Structure

```
vfit-gym-website/
│
├── vfit-gym-landing.html   ← Home page
├── about.html              ← About Us
├── programs.html           ← Training Programs
├── coaches.html            ← Coaches / Team
├── gallery.html            ← Photo Gallery
├── contact.html            ← Contact & Location
├── blog.html               ← Blog & Tips
└── README.md
```

All pages are self-contained — styles and scripts are embedded per file. No build step, no package manager, no framework required.

---

## Local Setup

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/vfit-gym-website.git

# Navigate into the folder
cd vfit-gym-website

# Open in browser — just double click any .html file
# Or use VS Code Live Server for best experience
```

No installs. No `npm install`. Just open and run.

---

## Deployment

Deployed on **Netlify** via drag-and-drop.

**To deploy your own copy:**

1. Go to [netlify.com](https://netlify.com)
2. Drag the entire project folder into the Netlify dashboard
3. Live in under 60 seconds

Or connect your GitHub repo to Netlify for auto-deploy on every push.

---

## Customisation Guide

| What to Change | Where |
|---|---|
| Gym name / logo | `nav-logo` in every file |
| Phone number | `contact.html` → info-blocks |
| Address | `contact.html` → info-blocks + map src |
| Membership prices | `vfit-gym-landing.html` → #membership |
| Coach names & bios | `coaches.html` |
| Hero images | Replace Unsplash URLs with your own photos |
| Color scheme | `:root` CSS variables at top of each file |
| Google Maps location | `contact.html` → iframe src |

---

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, animations, keyframes
- **Vanilla JS** — scroll events, IntersectionObserver, DOM manipulation
- **Google Fonts** — Bebas Neue, Barlow Condensed, Barlow
- **Unsplash** — placeholder imagery (replace with real gym photos)
- **Netlify** — hosting and deployment

---

## Screenshots

> Home · Programs · Coaches · Gallery · Contact · Blog

*(Replace with actual screenshots after deployment)*

---

## License

MIT License — free to use, modify, and deploy for personal or commercial gym projects.

---

## Built By

Designed and developed as a full static gym website project.  
Inspired by real local gyms focused on authentic fitness, transformation, and discipline.

**Live → [vfitmatrix-gym.netlify.app](https://vfitmatrix-gym.netlify.app/)**
