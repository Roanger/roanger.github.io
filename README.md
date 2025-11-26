# roanger.github.io

Portfolio scaffold for GitHub Pages.

## Local preview
Open `index.html` directly in a browser. GitHub Pages will serve it from the `main` branch when enabled.

## Content management
- `projects.json`: Add or update projects (title, description, tags, links, images).
- `images/`: Store portfolio images and reference them from `projects.json`.
- Workflow publishes on push to `main`.

## Deployment
Once merged to `main`, enable GitHub Pages in repository settings:
- Settings ? Pages ? Branch: `main` ? `/root`