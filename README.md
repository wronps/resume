# Yuyang Wang — Personal Website

Personal research and resume website, based on `Yuyang_Resume.pdf`.

**Website:** https://wronps.github.io/resume/

**Resume:** [Yuyang_Resume.pdf](Yuyang_Resume.pdf)

## Contents

- `index.html`: profile, research, projects, experience, education, skills, and contact information.
- `styles.css`: responsive styles, keyboard focus, reduced-motion support, and print layout.
- `script.js`: optional section highlighting in the navigation.
- `Yuyang_Resume.pdf`: the original resume, unchanged.

This is a static website with no build step, package dependencies, external fonts, analytics, or backend. The project diagrams are schematic illustrations, not experimental plots.

## Preview locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ in a browser.

## Update

Edit the text in `index.html` and replace `Yuyang_Resume.pdf` when the resume changes. The HTML is independent of the PDF; update both to keep them consistent. Research and manuscript status reflect the supplied resume.

## GitHub Pages

The site is served from the root of the `main` branch using GitHub Pages. Push changes to `main` to trigger a new deployment. In repository **Settings → Pages**, the source is **Deploy from a branch**, branch **main**, folder **/(root)**.
