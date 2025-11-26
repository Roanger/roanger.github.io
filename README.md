# Roanger — Portfolio

This repository hosts a simple portfolio website for showcasing projects.

How it works
- Edit `projects.json` to add your projects. Each entry contains title, description, url, demo, and tags.
- The site is a static HTML page that loads `projects.json`.
- GitHub Pages will serve this repository from the main branch root because the repo is named roanger.github.io.

Adding projects
- Open `projects.json` and add a new object:
  - title: "Project name"
  - description: "Short summary"
  - url: "https://github.com/username/repo"
  - demo: optional live link
  - tags: array of short tags

Optional enhancements
- Use a static site generator (Hugo/Next.js) for more features and prettier themes.
- Add a script to auto-discover your GitHub repos and generate `projects.json`.
- Add social preview images (og:image) and per-project screenshots.

If you want, I can:
- Add an auto-discovery script that fetches your repos and creates project entries.
- Convert this to a nicer theme (Jekyll/Hugo/Next) or integrate with a CMS.