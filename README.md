# Rakhi: personal site

Source of [chaad404.github.io](https://chaad404.github.io). It's a static site with no build step.

| File | What it is |
|---|---|
| `index.html` | The homepage: intro, news, research, experience, projects, education, about |
| `cv.html` | The academic CV (A4), source of the PDF |
| `Rakhi-CV.pdf` | The CV the site links to. Regenerate it from `cv.html` with **Print → Save as PDF** |
| `assets/css/style.css` | Styles, with light and dark themes |
| `assets/js/main.js` | Theme toggle, mobile menu and active nav link |
| `assets/img/` | Photos and favicon |

## Preview locally

```bash
python -m http.server 8000   # then open http://localhost:8000
```

## Updating

Edit the HTML, commit and push to `main`. GitHub Pages republishes within a minute or two.
When something changes, update the **News** list in `index.html` and the CV, then regenerate `Rakhi-CV.pdf`.
