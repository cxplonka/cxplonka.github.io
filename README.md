# cxplonka.github.io

Personal CV of Christian Plonka, built with Jekyll and served by GitHub Pages.

- **Theme:** "Dark Developer" — `assets/css/cv.css` (no frameworks, no JavaScript)
- **Fonts:** Inter and JetBrains Mono, self-hosted in `assets/fonts/` (SIL OFL 1.1), no requests to Google
- **Layout:** `_layouts/default.html` → `index.html` includes the sections from `_includes/`
  (`career-profile`, `experience`, `skills`, `projects`, `publications`, `education_training`, `header`, `footer`)
- **Profile data:** `_config.yml` (name, tagline, contact links)
- **Publications:** `_data/publications.yml` — newest first; `selected: true` shows an entry above the
  "show all" toggle, `type` is `journal`, `conference` or `software`, `doi` becomes a link automatically.

Local preview: `docker compose up` → http://localhost:4000
