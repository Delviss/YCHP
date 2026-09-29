# Local Setup

These docs are built with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material/) theme.

---

## Requirements

- Python 3.9+

---

## Run Locally

```bash
git clone https://github.com/Delviss/YCHP.git
cd YCHP
pip install -r requirements.txt
mkdocs serve
```

Open <http://127.0.0.1:8000>. The site reloads automatically as you edit files in `docs/`.

---

## Build

```bash
mkdocs build --strict
```

The static site is written to `site/` (git-ignored). `--strict` fails the build on broken links or warnings, the same check CI runs.

---

## Deployment

Every push to `main` builds the site and deploys it to **GitHub Pages** via `.github/workflows/pages.yml`:

<https://delviss.github.io/YCHP/>

!!! note "One-time setting"
    In the repository settings, **Settings → Pages → Build and deployment → Source** must be set to **GitHub Actions**.
