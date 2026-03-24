# Navigating Crisis — publication source (graphite-paper)

This repository contains the **source files** for the “Navigating Crisis” publication, prepared with **graphite-paper**.

## Published version
Read the published publication here:

- https://graphite.page/hiig-navigating-crisis

## Repository layout

- `paper/` — the graphite-paper “paper folder” (contains `manage.py` and all publication source files)
- Root files (this directory) — license, citation metadata, and documentation

## How to reproduce / build locally

This repo stores the source; to build locally you need the graphite-paper environment.

1. Install graphite-paper following the docs:
   - https://graphite-paper.readthedocs.io/en/latest/

2. Build the publication:

```bash
python paper/manage.py build
```

3. (Optional) Run a local preview server:

```bash
python paper/manage.py runserver
```

## License
Licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See `LICENSE`.

## Citation / DOI
Once a DOI is minted (e.g., via Zenodo + GitHub Releases), please use the repository’s “Cite this repository” information on GitHub or the DOI record.