# Academic Professor Portfolio Website (Hugo + PaperMod)

A clean, structured, and professional **academic portfolio website** designed specifically for **university professors, researchers, and faculty members**.

This project focuses on **research visibility, publications, and academic credibility**, not flashy marketing pages.  
It is suitable for showcasing faculty profiles, research work, publications, awards, and academic activities.

---

## ✨ Features

- **Clean academic homepage**
  - Name, designation, research focus
  - CV download and contact links
  - Google Scholar & ORCID integration

- **Publications system**
  - Publications grouped by **year**
  - Support for **Journal Articles** and **Conference Papers**
  - Optional **PDF** and **DOI** buttons
  - Clean, citation-style layout

- **Selected academic sections**
  - Research
  - Teaching
  - Awards
  - Workshops
  - Contact

- **Minimal & professional design**
  - No unnecessary animations
  - No clutter
  - Academic-first typography and spacing

- **Easy to maintain**
  - Content written in Markdown
  - PDFs served directly from `static/`
  - Single config file
  - Suitable for non-technical users after setup

---

## 🧱 Tech Stack

- **Hugo (Extended)** – Static site generator  
- **PaperMod Theme** – Clean, fast, and accessible  
- **Markdown + TOML** – Simple content & configuration  

No database. No backend. No CMS required.

---

## 📁 Project Structure (Simplified)
prof-portfolio/
├── content/
│ ├── _index.md # Homepage content
│ ├── publications/ # Publications (one file per paper)
│ ├── research/
│ ├── teaching/
│ ├── awards/
│ ├── workshops/
│ └── contact/
│
├── layouts/
│ ├── index.html # Custom homepage layout
│ └── publications/
│ └── list.html # Publications layout
│
├── assets/
│ └── css/
│ └── custom.css # Custom styling
│
├── static/
│ └── files/
│ ├── cv.pdf
│ └── papers/
│ └── sample-paper.pdf
│
├── hugo.toml # Main configuration
└── README.md



---

## 📝 Adding a Publication (Example)

Create a new file inside `content/publications/`:

```md
---
title: "Climate Change Impacts on Semi-Arid Ecosystems"
authors:
  - A. Sharma
  - B. Kumar
year: 2023
journal: "Environmental Research Letters"
pubtype: "Journal Article"
doi: "https://doi.org/10.xxxx/xxxx"
pdf: "/files/papers/sample-paper.pdf"
---
Fields like pdf, doi, or pubtype are optional.

📄 Adding / Updating CV

Place the CV file here:

static/files/cv.pdf


The link /files/cv.pdf will always work.
To update the CV, simply replace the file — no code changes needed.

Running Locally
1. Install Hugo (Extended version)

https://gohugo.io/getting-started/installing/

2. Start development server
hugo server


Open in browser:

http://localhost:1313/

🌍 Deployment

This site is ready to be deployed on:

Netlify

GitHub Pages

Any static hosting provider

(No backend or server required.)

🎯 Intended Use

University professors

Academic researchers

Faculty members

Research scholars

Academic pilot projects or student-led initiatives

📌 Note

This project prioritizes:

academic credibility

clarity

long-term maintainability

It intentionally avoids heavy animations or marketing-style UI.
