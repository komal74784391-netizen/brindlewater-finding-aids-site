# Brindlewater Archive — public finding aids

Static site source for the archive's public finding-aid catalogue.

- `collections/` — one Markdown entry per collection; the build reads YAML
  front matter and renders the body below it.
- `catalogue/design_package_inventory.csv` — nightly generated export of
  candidate digitisation repositories (do not edit by hand).

Build: `python build.py` (the renderer is kept in the archive's tooling repo).
