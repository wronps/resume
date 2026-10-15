# Yuyang Wang — Curriculum Vitae

A plain, single-column HTML resume following the content and section order of `Yuyang_Resume.pdf`.

**Website:** https://wronps.github.io/resume/

**Resume:** [Yuyang_Resume.pdf](Yuyang_Resume.pdf)

## Contents

- `index.html`: contact information, education, experience, projects, and technical skills.
- `styles.css`: typography, mobile layout, keyboard focus, and print styles.
- `Yuyang_Resume.pdf`: the original resume, unchanged.

This is a static website with no JavaScript, build step, package dependencies, external fonts, analytics, or backend.

## Preview locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ in a browser.

## Update

Edit the text in `index.html` and replace `Yuyang_Resume.pdf` when the resume changes. The HTML is independent of the PDF; update both to keep them consistent. Research and manuscript status reflect the supplied resume.

## GitHub Pages

The site is served from the root of the `main` branch using GitHub Pages. Push changes to `main` to trigger a new deployment. In repository **Settings → Pages**, the source is **Deploy from a branch**, branch **main**, folder **/(root)**.
