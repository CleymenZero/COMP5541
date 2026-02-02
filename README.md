# COMP5541 — UML Diagrams (diagrams.net / draw.io)

This repository contains UML diagrams for the COMP5541 project, authored with diagrams.net (draw.io). Source files live in `diagrams/` as `.drawio` (XML) files; exported images (PNG/SVG) live in `diagrams/exported/` so they can be embedded in markdown and shown on GitHub.

## Quick links
- diagrams directory: `diagrams/`
- templates: `diagrams/templates/`
- exported images: `diagrams/exported/`

## How to edit diagrams
Recommended options:
- Use the web editor at https://www.diagrams.net/ and save the file locally, then push.
- Use the diagrams.net desktop app (File → Save) to update the `.drawio` file.
- Use the VS Code Draw.io Integration extension to edit and save `.drawio` files inside the repo.

Editing steps:
1. Clone the repo and create a branch.
2. Open or create `.drawio` files in `diagrams/`.
3. Save your changes (the `.drawio` file is the canonical source).
4. Optionally export a PNG/SVG (File → Export As → PNG/SVG) and place it in `diagrams/exported/`.
5. Commit and open a PR.

## Automated exports
This repository includes an example GitHub Actions workflow that can auto-export `.drawio` files to PNG/SVG on push (see `.github/workflows/export-diagrams.yml`). The workflow uses a CLI/container capable of headless export; update the workflow if you prefer a specific exporter.

## Gallery
Rendered diagrams are displayed in this README (or in `docs/`) by linking to the files in `diagrams/exported/`.

Example:
![Example UML](diagrams/exported/example-class-diagram.png)

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines and templates.

## Repository topics
Consider adding topics: `drawio`, `diagrams`, `uml`, `uml-diagrams`, `diagrams.net`
