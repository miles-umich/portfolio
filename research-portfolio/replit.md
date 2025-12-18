# Academic Portfolio Website - M. Miles

## Overview
A minimalist, high-end design portfolio website for Margaret Miles, a PhD student in Human-Computer Interaction (HCI) at the University of Michigan. Built with clean HTML, CSS, and JavaScript.

## Project Structure
```
├── index.html                 - Main page with all sections
├── style.css                  - All styling
├── script.js                  - Mobile navigation and animations
├── server.py                  - Python HTTP server with cache control
├── design-projects.html       - All design projects archive page
├── mindflow-project.html      - Design project detail page
├── accesslab-project.html     - Design project detail page
├── datastory-project.html     - Design project detail page
├── research/
│   ├── parametric-insurance.html  - Research detail page
│   ├── flood-information.html     - Research detail page
│   └── non-recovery.html          - Research detail page
└── images/                    - Project images
```

## Design Features
- **Typography**: Calibri (with Segoe UI fallback)
- **Color Palette**: 
  - Primary: Deep Slate (#2d3436)
  - Accent: Dark Blue (#1e3a5f)
- **Layout**: Generous white space, clean academic aesthetic

## Page Structure
### Main Page (index.html)
1. **About** - Hero section with name, title, and research description
2. **Research** - CSS Grid of clickable research cards (link to detail pages)
3. **Design Projects** - 3 most recent projects as cards with "See more" link
4. **Publications** - Clean bibliography-style listing
5. **CV** - Two-column education and experience layout

### Detail Pages
- Research detail pages include: overview, research questions, methodology, status
- Design project pages include: project preview image, overview, challenge, approach

## Running the Project
The site is served via Python's HTTP server on port 5000 with cache control disabled.

## Customization
Update content in HTML files with actual:
- Research project details
- Design project descriptions and images
- Publications
- CV details
- Contact links