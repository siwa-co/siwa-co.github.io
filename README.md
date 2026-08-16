# Portfolio Website - Ibrahim Hassan

A hand-crafted, dark-themed developer portfolio built from scratch with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies.

**Live:** [inboxibrahim.github.io](https://inboxibrahim.github.io)

## Overview

Personal portfolio for Ibrahim Hassan - AI Engineer & Solution Architect specializing in speech AI, LLMs, OCR, and scalable ML systems. The site serves as a centralized showcase for open-source projects, each with a dedicated deep-dive page covering motivation, architecture, code walkthroughs, and screenshots.

## Features

- **Cinematic landing page** with typing animation and logo glitch effect
- **Project showcase grid** with thumbnail cards, tech tags, and pointer-tracked glow on hover
- **Deep project pages** - each project gets a full write-up with overview, motivation, screenshots, tech stack, code samples, and challenges
- **About page** with professional background, skills, and contact links
- **Dark theme** with carefully tuned surface hierarchy and accent colors
- **Fully responsive** across mobile, tablet, and desktop
- **SEO-optimized** with Open Graph, Twitter Cards, canonical URLs, and structured meta on every page
- **Code blocks with copy buttons** for easy sharing of technical content
- **Intersection Observer animations** for smooth fade-in on scroll
- **Zero dependencies** - pure HTML, CSS, and JS deployed directly to GitHub Pages

## Project Structure

```
inboxibrahim.github.io/
├── index.html              # Landing page
├── index.css               # Shared design system (single stylesheet)
├── all-projects.html       # Project showcase grid
├── about.html              # About & contact page
├── under-dev.html          # Placeholder for upcoming project pages
├── assests/
│   ├── favicon.ico
│   ├── Original.png
│   └── Resume.pdf
└── projects/
    ├── project-1.html      # Individual project deep-dive pages
    ├── project-2.html
    ├── ...
    └── resources/
        ├── project-1/      # Screenshots and assets per project
        ├── project-2/
        └── ...
```

## Technologies

| Layer | Tools |
|-------|-------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Design system** | CSS Custom Properties, CSS Grid, Flexbox, `clamp()` fluid typography |
| **Interactions** | Intersection Observer API, Pointer Events, Clipboard API |
| **Hosting** | GitHub Pages |
| **SEO** | Open Graph, Twitter Cards, canonical URLs |

## Adding a New Project

1. Create `projects/project-N.html` using an existing project page as the template
2. Add screenshots to `projects/resources/project-N/`
3. Add a project card to `all-projects.html` inside the `.projects-grid`

No build step required - edit, commit, and push.

## Local Development

Open `index.html` in any browser. No server or tooling needed.

## Contact

- **Email:** [ih403020@gmail.com]
- **LinkedIn:** [https://www.linkedin.com/in/ibrahim-hassan-326319269/](https://www.linkedin.com/in/ibrahim-hassan-326319269/)
- **GitHub:** [github.com/siwa-co](https://github.com/siwa-co)


## License

© 2026 Ibrahim Hassan. All rights reserved.
