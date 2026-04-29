# Hetarth Salat — Portfolio Website

A clean, professional, multi-page portfolio built with semantic HTML5 and handwritten CSS.  
No frameworks. No build tools. Just solid fundamentals — as it should be.

**Theme:** Deep Winter (Navy · Slate · White · Accent Blue)  
**Author:** Hetarth Salat — B.Tech CSE (AI/ML), Parul University, Vadodara  
**GitHub Profile:** [@Skullcrusher161](https://github.com/Skullcrusher161)

---

## Project Structure

```
portfolio/
│
├── index.html            → Home page: Hero, Foundational Narrative, Tech Stack Grid
├── certificates.html     → Certificate gallery with hover-lift cards
├── contact.html          → About Me narrative + Email / LinkedIn / GitHub links
├── resume.html           → Embedded PDF viewer + download button
│
├── style.css             → Universal external stylesheet (all pages share this)
│
├── README.md             → This file — project documentation
├── .gitignore            → Standard exclusions for web projects
│
└── assets/               → All static files (images & PDF)
    ├── cert-python-ibm.jpg
    ├── cert-htmlcss-ethnotech.jpg
    ├── cert-prompt-simplilearn.jpg
    ├── cert-hackathon-vadodara.jpg
    └── hetarth-salat-resume.pdf
```

---


## CSS Architecture Notes

All styles live in a single `styles.css`. The file is organised into clearly labelled sections:

1. CSS Custom Properties (design tokens — colours, fonts, spacing)
2. Reset & Base
3. Typography
4. Layout Utilities (`.container`, `.section`)
5. Navbar (sticky, frosted-glass effect via `backdrop-filter`)
6. Hero
7. Narrative Section
8. Tech Stack Grid
9. Certificates Grid
10. Contact Layout
11. Resume Embed
12. Footer
13. Animations (`fadeUp`, staggered delays)
14. Responsive breakpoints (900px, 650px, 420px)

---

*Built with ❤ and handwritten CSS — no frameworks were harmed in the making of this portfolio.*