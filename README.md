# The Lands Between — Elden Ring Progression Companion

A lightweight, self-contained Elden Ring checklist web app for GitHub Pages.

## Features
- 18-region recommended progression route
- Curated Sites of Grace checklist and boss checklist per region
- NPC questline summaries
- Mutually exclusive quest outcomes and progression lockout warnings
- Base-game ending checklist
- Search across region checklist items
- Browser-local progress persistence (`localStorage`)
- No build step, backend, API key, or external dependency

## Deploy to GitHub Pages
1. Create a GitHub repository (for example `elden-ring-companion`).
2. Put `index.html` in the repository root.
3. Commit and push to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for GitHub Pages to publish the site.

Your site will be available at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Notes
- This is an unofficial fan-made companion for the base game.
- Suggested levels are approximate.
- Grace lists are curated route anchors, not a guaranteed exhaustive inventory of every Site of Grace in every dungeon.
- Checklist state is stored in the browser/device where the site is used. It does not sync between devices or browsers.
- The app intentionally uses plain HTML, CSS and JavaScript so it can be hosted directly on GitHub Pages.
