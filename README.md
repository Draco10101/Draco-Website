# DRACO1010 — Portfolio Website

**Live portfolio:** https://draco10101.github.io/Draco-Website/

This repository contains the DRACO1010 public portfolio website. It is the primary portfolio publishing repository; keep the website source, styles, scripts, and media assets together here.

## Repository layout

```text
.
├── .devcontainer/       # Development-container configuration
├── .nojekyll            # Prevents GitHub Pages from processing the site with Jekyll
├── index.html           # Website entry point
├── README.md            # Project documentation
└── assets/              # Add shared CSS, JavaScript, and image assets here as needed
    ├── css/
    ├── js/
    └── images/
```

The `assets/` folders are the recommended location for new shared assets. Preserve existing paths and update references in the HTML whenever files are moved.

## Portfolio focus

The portfolio presents work and capabilities across:

- IT support and technology consulting
- Web development and website maintenance
- Data analysis
- Design and digital content
- Technical projects and experiments

## Local development

1. Clone the repository.
2. Open `index.html` in a browser or a local development server.
3. Check all navigation, external links, images, and responsive layouts.
4. Test on both mobile and desktop screen sizes.
5. Review the Git diff before publishing.

No build step is required for a plain static HTML/CSS/JavaScript site unless one is introduced later.

## GitHub Pages

The site is published from this repository:

https://draco10101.github.io/Draco-Website/

Keep `index.html` at the repository root unless the Pages source configuration is deliberately changed.

## Maintenance rules

- Preserve existing website content, working assets, and backups.
- Do not commit API keys, passwords, tokens, private customer information, or other secrets.
- Use descriptive commits and review changes before merging.
- Do not copy the whole website into `PortfolioDraco10101`; keep one canonical published copy.
- Keep business-client websites in their own repositories.

## Related repositories

- [Bianca-website](https://github.com/Draco10101/Bianca-website) — separate client/business website.
- [Shizuku-API](https://github.com/Draco10101/Shizuku-API) — Android development/reference project.
- [DRACO1010-Termux-Backup](https://github.com/Draco10101/DRACO1010-Termux-Backup) — private Termux backup repository; do not expose its contents in public documentation.
