# DRACO1010 — Web Portfolio

This repository is the GitHub Pages portfolio scaffold for the DRACO1010 brand.

## Current repository status

The current default branch contains the development-container configuration and this README. It does **not** yet contain the portfolio website entry point (`index.html`) or its CSS, JavaScript, and image assets.

GitHub Pages is enabled for this repository, but the website is not ready to publish as a complete portfolio until the site source is added.

## Recommended structure

```text
.
├── index.html
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── README.md
└── .devcontainer/
    └── devcontainer.json
```

Keep the current `.devcontainer/` configuration. Add the real portfolio source and assets from the maintained working copy; do not replace them with placeholder files.

## Publishing checklist

1. Back up the working portfolio folder.
2. Add the real `index.html` and referenced assets.
3. Check all relative paths and links.
4. Preview the site on mobile and desktop.
5. Open a pull request and verify its file diff.
6. Merge only after the page loads correctly from GitHub Pages.

## Maintenance

Use feature branches for changes. Preserve existing commits and backups; do not force-push or delete source files during cleanup.