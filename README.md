# Ashen Wilds Wiki

The player guide for Ashen Wilds, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and published to GitHub Pages:
https://liquid-gorrila.github.io/ashen-wilds-wiki/

## Editing

Pages live in `docs/` as Markdown, one file per page. The sidebar order is the `nav` list in `mkdocs.yml`.

Every push to `main` rebuilds and republishes the site through `.github/workflows/docs.yml`, usually within a minute or two. You can edit a page directly on GitHub (each page on the site has an edit button) or locally.

## Preview locally (optional)

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000.
