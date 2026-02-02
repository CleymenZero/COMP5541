# Contributing to COMP5541 UML diagrams

Thanks for helping document the project with diagrams! Please follow these guidelines.

## File conventions
- Source diagram files: `diagrams/*.drawio` (this XML file is the source of truth).
- Templates: `diagrams/templates/`.
- Exported images: `diagrams/exported/` (PNG/SVG) — recommended but optional to commit.

## Branch/PR workflow
1. Create a branch named `diagram/<short-description>`.
2. Edit or add `.drawio` files under `diagrams/`.
3. If adding a new exported image for the gallery, put it in `diagrams/exported/`.
4. Commit with a descriptive message and open a PR targeting `main`.
5. In the PR description include:
   - What the diagram documents.
   - Which files you changed.
   - Any special export options (e.g., transparent background).

## Editing tips
- Keep one main diagram per `.drawio` file.
- Use descriptive filenames: `usecase-authentication.drawio`, `class-user-account.drawio`.
- Prefer vector export (SVG) for diagrams with text; use PNG for raster screenshots.

## Review checklist
- [ ] The `.drawio` source is included and renders correctly in diagrams.net.
- [ ] The exported image(s) show the diagram and text at readable resolution.
- [ ] Filenames and placement follow the conventions.
