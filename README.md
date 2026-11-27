# Matías Gangui – Portfolio

Personal portfolio of **Matías Gangui**, AI Engineer and Data Science student at the University of Buenos Aires (UBA).

**Live site:** https://mgangui.github.io

## What's on the site

- **Studies:** BS + MSc in Data Science at UBA, with coursework and GPA.
- **Experience:** data engineering and analytics work at Baufest (Chipotle and Les Schwab).
- **Projects:** urban mobility optimization, hierarchical Bayesian estimation of football market prices, layoffs prediction and recommendation systems.
- **Skills and certifications:** AI engineering, data engineering and cloud, BI, advanced analytics, languages and tools.
- **Contact:** email, LinkedIn, UpWork and CV downloads in English and Spanish.

## Features

- Interactive hero chart: a slider shows how a Bayesian posterior narrows around the true value as more data comes in.
- Light and dark themes, following the system setting, with a toggle that remembers the choice.
- Sticky navigation that highlights the current section, plus a scroll progress bar.
- "Copy email" button in the contact section.
- CV downloads in English and Spanish.
- Responsive layout, keyboard-friendly, and respects the "reduce motion" setting.

## Repository structure

```
.
├── index.html                       # The whole site: HTML, CSS and JavaScript
├── CV Matias Gangui - English.pdf   # CV (English)
├── CV Matias Gangui - Español.pdf   # CV (Spanish)
└── README.md
```

The site is a single static file with no build step and no dependencies. The only external resource is the Google Fonts stylesheet (Bricolage Grotesque and Public Sans), and the page falls back to system fonts if it can't load.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Edit the content

- **Text, experience and projects:** edit the sections in `index.html` (`#education`, `#experience`, `#projects`, `#skills`, `#contact`).
- **Colors:** change the CSS variables at the top of the `<style>` block (`--bg`, `--ink`, `--accent` and so on). The dark theme has its own values just below.
- **CVs:** replace the two PDFs, keeping the same file names. The download buttons in `index.html` point to them.

## Deploy

The site is published with GitHub Pages from the `main` branch. Push a change to `index.html` or the PDFs and the site updates within a minute or two.

## Contact

- Email: ganguimatias@gmail.com
- LinkedIn: https://www.linkedin.com/in/matiasgangui/
- UpWork: https://www.upwork.com/freelancers/~01871492960f6243cb
