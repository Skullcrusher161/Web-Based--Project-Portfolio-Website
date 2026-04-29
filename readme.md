# Hetarth Salat — Portfolio

A clean, professional, multi-page portfolio hand-built with semantic HTML5 and CSS3.  
No frameworks. No build tools. Pure fundamentals — exactly the philosophy it represents.

> **Live Demo:** `https://Skullcrusher161.github.io/<repo-name>/`  
> **Author:** Hetarth Salat — B.Tech CSE (AI/ML), Parul University, Vadodara  
> **Theme:** Deep Winter (Navy · Slate · Ice Blue)

---

## Project Structure

```
portfolio/
│
├── index.html              →  Home — Hero, Foundations Narrative, Tech Stack Grid
├── certifications.html       →  Large-format certificate gallery (hover-lift cards)
├── resume.html             →  Inline HTML resume + PDF download button
├── contact.html            →  About Me narrative + Email / LinkedIn / GitHub links
│
├── style.css               →  Universal stylesheet (ALL pages share this file)
│
├── README.md               →  You are here
├── .gitignore              →  Standard web project exclusions
│
└── assets/                 →  Static files — images and PDF
    ├── cert-python-ibm.jpg            ← IBM Python certificate screenshot
    ├── cert-htmlcss-ethnotech.jpg     ← Ethnotech HTML/CSS cert screenshot
    ├── cert-prompt-simplilearn.jpg    ← Simplilearn Prompt Engineering cert
    ├── cert-hackathon-vadodara.jpg    ← Vadodara Hackathon 6.0 cert/photo
    └── hetarth-salat-resume.pdf       ← Your resume as a PDF (for download)
```

---

## Page Overview

| File | URL Path | Contents |
|---|---|---|
| `index.html` | `/` | Hero section, Foundations narrative, 4-col Tech Stack grid |
| `certificates.html` | `/certifications.html` | Full-width certificate cards (alternating layout, hover lift) |
| `resume.html` | `/resume.html` | Inline styled resume: Education, Projects, Skills, Certs + PDF download |
| `contact.html` | `/contact.html` | About Me narrative + Email, LinkedIn, GitHub contact links |

---

## CSS Architecture

`style.css` is one file, organised into clearly labelled sections:

| Section | What it controls |
|---|---|
| CSS Custom Properties | All colour tokens, fonts, spacing, shadows |
| Reset & Base | Universal box-sizing, body defaults |
| Typography | h1–h4, p, a, strong |
| Layout Helpers | `.wrap`, `.section`, `.eyebrow`, `.rule` |
| Buttons | `.btn-solid`, `.btn-ghost` |
| Navbar | Sticky frosted-glass nav with mobile burger |
| Home — Hero | Title, role, body, CTA buttons |
| Home — Narrative | 2-col grid, pull quote, pillar items |
| Home — Tech Grid | 4-col card grid with status badges |
| Certificates | Large alternating card layout |
| Resume | Header band, 2-col body, skill bars, sidebar certs |
| Contact | 2-col grid, contact link cards, facts table |
| Footer | Minimal 2-column footer |
| Animations | `fadeUp` keyframes with staggered delays |
| Responsive | Breakpoints at 960px, 640px, 400px |

---

*Built with patience and handwritten CSS — no frameworks, no shortcuts, no apologies.*