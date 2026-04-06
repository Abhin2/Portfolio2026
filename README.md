# Abhishek Nagar — Portfolio Website

> A Portavia-inspired personal developer portfolio built with pure HTML, CSS, and JavaScript. Designed to showcase AI/ML engineering work with a clean, minimal aesthetic.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## Live Demo

🔗 **[View Portfolio →](https://abhin2.github.io)**

---

## Overview

This portfolio is inspired by the **Portavia** template from Framer Marketplace — adapted and hand-coded from scratch using vanilla web technologies. It features a warm off-white aesthetic, editorial serif typography (Cormorant Garamond + Geist), a floating pill navbar, animated marquee ticker, and smooth scroll-reveal interactions.

---

## Features

- **Portavia-inspired design** — warm `#f9f8f5` background, editorial serif headings, generous whitespace
- **Floating glassmorphism navbar** — pill-shaped, sticky, backdrop blur
- **Animated marquee** — scrolling tech stack ticker
- **Hero profile card** — contact info + stats sidebar
- **Services section** — numbered expertise breakdown
- **Project cards** — hover animations with rotating arrow indicator
- **Scroll reveal** — sections and cards fade in on scroll via IntersectionObserver
- **Custom cursor** — dot + trailing ring follower
- **Responsive design** — works across desktop, tablet, and mobile
- **Zero dependencies** — no frameworks, no build tools, single HTML file
- **Contact form** — ready to wire up to any backend or Formspree

---

## Sections

| Section | Description |
|---|---|
| Hero | Name, title, bio, CTA buttons, profile card, stats |
| Marquee | Scrolling ticker of all technologies |
| What I Do | Numbered expertise areas |
| Projects | Featured project cards with tech chips |
| Skills | Tag-based skill groups (AI/ML, Python, Cloud) |
| Experience | Timeline of internships |
| Education | B.Tech + Senior Secondary |
| Certifications | All 6 credentials |
| Contact | Form + direct contact links |

---

## Tech Stack

```
HTML5          — Structure and semantics
CSS3           — Layout, animations, custom properties
JavaScript     — Cursor, scroll reveal, IntersectionObserver
Google Fonts   — Cormorant Garamond (display) + Geist (body)
```

No npm. No webpack. No React. Just a single `.html` file — open it and it works.

---

## Getting Started

### Option 1 — Open directly

```bash
git clone https://github.com/Abhin2/portfolio.git
cd portfolio
open index.html
```

### Option 2 — Serve locally

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then open `http://localhost:8000` in your browser.

---

## Customization

All content is in a single `index.html` file. To make it yours:

### Update personal info
Search and replace the following placeholders:

```
Abhishek Nagar        → Your name
nagarabhi49@gmail.com → Your email
+91 63786 25317       → Your phone
github.com/Abhin2     → Your GitHub
linkedin.com/in/abhii-n → Your LinkedIn
Jaipur, India         → Your location
```

### Update the hero section
```html
<h1 class="hero-name">
  <span class="highlight">Your</span><br>Name
</h1>
<p class="hero-title">Your Role · Your Stack</p>
<p class="hero-bio">Your bio goes here...</p>
```

### Add or remove projects
Copy a `.project` block and update the content:

```html
<div class="project">
  <div class="project-num">Project 01</div>
  <div>
    <div class="project-cat">Your Category</div>
    <div class="project-title">Project Title</div>
    <p class="project-desc">Project description...</p>
    <div class="project-chips">
      <span class="chip">Tech1</span>
      <span class="chip">Tech2</span>
    </div>
  </div>
  <div class="project-arrow">↗</div>
</div>
```

### Change fonts
Replace the Google Fonts import at the top:

```css
@import url('https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap');
```

---

## Deployment

### GitHub Pages (recommended — free)

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Netlify (drag & drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder
3. Done — live in seconds with a custom URL

### Vercel

```bash
npm install -g vercel
vercel
```

---

## Design Credits

Aesthetic inspired by **[Portavia](https://www.framer.com/marketplace/templates/portavia/)** by [oldshen](https://www.framer.com/@duncan/) on Framer Marketplace.

Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) · [Geist](https://vercel.com/font) by Vercel

---

## Project Structure

```
portfolio/
│
├── index.html        # Everything — HTML, CSS, JS in one file
└── README.md         # This file
```

The entire portfolio is intentionally a single file for maximum portability and simplicity.

---

## Contact

**Abhishek Nagar**
AI / ML Engineer · Jaipur, India

- Email: [nagarabhi49@gmail.com](mailto:nagarabhi49@gmail.com)
- LinkedIn: [linkedin.com/in/abhii-n](https://linkedin.com/in/abhii-n)
- GitHub: [github.com/Abhin2](https://github.com/Abhin2)

---

## License

MIT License — free to use, modify, and distribute. Attribution appreciated but not required.

```
MIT License

Copyright (c) 2026 Abhishek Nagar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

*Built with care. No frameworks harmed.*
