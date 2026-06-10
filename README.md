# The Long Goodbye — V5.7.10 Full JP Deploy Build

This package contains the corrected bilingual English/Japanese visual novel build.

## Important deploy structure

Upload these items to the SAME GitHub Pages folder/repo root:

- `index.html`
- `assets/`
- `ASSET_MANIFEST.csv`
- `README.md`

Do not paste the HTML directly into Google Sites. The images use relative paths like `assets/...`, so the `assets/` folder must be hosted beside `index.html` on GitHub Pages.

## Fixes in this package

- EN/和 language toggle is now global and visible throughout gameplay, endings, gallery, saves, and menus.
- `index.html` image references were checked against the included `assets/` folder.
- Japanese route/story/endings remain mapped to the same image assets as English.
- Harrison bittersweet/bad ending art remains mapped correctly.
- Japanese locked menu uses `隠しルート`.

## Verification

- Referenced image paths in `index.html`: 258
- Missing referenced assets: 0
- Non-JPEG/JPG asset files: 0

If images do not appear after deployment, confirm GitHub Pages contains `assets/` at the same level as `index.html`, not inside another nested folder.
