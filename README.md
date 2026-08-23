# Bo Yang — Personal Research Homepage

A dependency-free, multi-page academic website for GitHub Pages, built with semantic HTML, custom CSS, and a small progressive-enhancement script. Each academic section has its own page.

## Local preview

From the repository root, run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publishing

The site is designed for the root user URL `https://megumi-ybb.github.io/`. The GitHub repository should therefore be named `megumi-ybb.github.io`, with Pages configured to deploy from `main` and `/(root)`.

The original `Bo_Yang_cv.pdf` remains intentionally ignored. The phone-free public version is stored at `assets/pdf/bo-yang-cv.pdf` and linked from the homepage.

## Maintenance

- Update the academic profile in `index.html`.
- Update section content in `research.html`, `publications.html`, `education.html`, `honors.html`, and `cv.html`.
- Update the visual system in `assets/css/styles.css`.
- Keep publication statuses and external links verified against official sources.
- Do not add Codex or local agent files to version control; the repository `.gitignore` contains the required exclusions.
