# DRACO1010 — Web Portfolio

This repository is the GitHub Pages portfolio scaffold for the DRACO1010 brand.

## Current repository status

The `main` branch contains the published portfolio entry point (`index.html`) and its embedded CSS and JavaScript. The page includes the DRACO1010 profile, skills, featured projects, live public GitHub profile/repository data, and contact section.

GitHub Pages is configured for this repository. Verify the published page after merging changes to `main`.

## Recommended structure

```text
.
├── index.html
├── README.md
└── .devcontainer/
    └── devcontainer.json
```

Keep the current `.devcontainer/` configuration. Add the real portfolio source and assets from the maintained working copy; do not replace them with placeholder files.

## Publishing checklist

1. Back up the working portfolio folder.
2. Review the existing `index.html` and any referenced assets.
3. Check all external contact links and relative paths.
4. Preview the site on mobile and desktop.
5. Open a pull request and verify its file diff.
6. Merge only after the page loads correctly from GitHub Pages.

## Maintenance

Use feature branches for changes. Preserve existing commits and backups; do not force-push or delete source files during cleanup.