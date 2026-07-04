# Verdigris — documentation site

Public documentation for **Verdigris**, an S3-native log storage & query engine.
The source code is maintained privately; this repo holds only the docs and the
MkDocs site that publishes them to GitHub Pages.

**Live site:** https://explise.github.io/verdigris-docs/

## Local preview

```bash
pip install mkdocs-material
mkdocs serve      # → http://127.0.0.1:8000
```

## Publish

The site is served from the `gh-pages` branch. To rebuild and publish:

```bash
mkdocs gh-deploy --force
```

(GitHub Pages on a public repo is free and does not consume Actions minutes.)
