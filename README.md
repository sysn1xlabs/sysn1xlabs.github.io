# sysn1xlabs — Independent Lab

A responsive, dependency-free portfolio for GitHub Pages. Built with semantic HTML, CSS, inline SVG, and vanilla JavaScript. No tracking, external fonts, runtime libraries, or build step.

## Preview
Open `index.html` directly in a browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish to GitHub Pages
1. Create a public repository named `sysn1xlabs.github.io` under `sysn1xlabs`.
2. Upload `index.html` and `.nojekyll` to the root of its `main` branch (include the hidden `.nojekyll` file).
3. In Settings → Pages, choose **Deploy from a branch**, then **main** and **/(root)**, and Save.
4. When deployment completes, visit https://sysn1xlabs.github.io/.

The portfolio also works in a project repository because it uses relative/local assets.

## Edit
All content and styling live in `index.html`. Edit the project cards, descriptions, GitHub links, and about section there. Project status labels are deliberate: NodeNix is a public repository, ApplyNix and Joe Goldberg are in development, and SecureSweep is a concept. Terminal and document graphics are illustrative, not product screenshots.

## Features
- Responsive editorial layout with a CSS orbital illustration.
- Project category filters with accessible state announcements.
- Searchable command palette: Ctrl+K / Cmd+K, Escape to close.
- Keyboard focus states, skip link, semantic landmarks, reduced-motion support.
- Alias-only content; no personal contact information.

## Credits
Created for sysn1xlabs. MIT licensed; see LICENSE.
