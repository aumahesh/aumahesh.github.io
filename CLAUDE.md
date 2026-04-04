# CLAUDE.md — aumahesh.github.io

Personal website for Mahesh Arumugam (software architect).

## Structure

Single-page site — everything is in `index.html`. No build system.

- CSS is inline in the `<style>` block in the `<head>`.
- JS is inline at the bottom of `<body>` (scroll fade-in + active nav link logic).
- PDFs for publications and projects are in `papers/`.
- Deployed via GitHub Actions to GitHub Pages (`.github/workflows/deploy.yml`).

## Design principles

- Minimal and clean — avoid decorative elements that don't serve content.
- Readable at all viewport sizes — mobile-first responsive layout.
- Font: Inter (sans-serif body) + JetBrains Mono (labels/tags/nav).
- Color palette: white background, neutral gray text hierarchy, single blue accent (`--accent: #1a56db`).
- No JavaScript frameworks or external dependencies beyond Google Fonts.

## Editing guidelines

- Keep all styles in the single `<style>` block; do not create a separate CSS file.
- Use CSS custom properties (`--ink`, `--paper`, `--accent`, etc.) for all colors and fonts.
- Maintain the existing section order: hero → experience → projects → publications → about → contact.
- Do not add new sections without being asked.
