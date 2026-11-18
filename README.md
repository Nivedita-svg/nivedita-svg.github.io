# Nivedita Sudhir Patil · Business Analytics Portfolio

Source for [nivedita-svg.github.io](https://nivedita-svg.github.io).

## How it's built

Plain static HTML, CSS and a small JavaScript file. There is no build step: GitHub Pages
serves the files as they are (`.nojekyll` turns off Jekyll processing).

- Fonts (Fraunces and Inter, SIL Open Font License) are self-hosted in `assets/fonts/`, so
  the site makes no third-party requests.
- No analytics, trackers, comment systems or contact forms.

| Page | File |
|---|---|
| Home | `index.html` |
| About | `about/index.html` |
| Experience | `experience/index.html` |
| Projects | `projects/index.html` |
| Case studies | `projects/<name>/index.html` |
| Styles | `assets/css/style.css` |

## Credit and license

This site started from the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
Jekyll theme by Michael Rose (MIT). It has since been redesigned from scratch. The original
MIT notice is kept in `LICENSE`, and the credit appears in the site footer.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publishing

GitHub Pages: Settings → Pages → Deploy from a branch → `master` / `(root)`.

## Rules

No résumé/CV, phone number, home address, birth date or ID numbers on this site. Every
claim must trace to my own records. Client work stays anonymous unless the client clears it.
