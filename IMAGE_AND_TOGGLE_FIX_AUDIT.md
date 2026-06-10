# Image and Toggle Fix Audit

## Results

- Global EN/和 toggle: added outside all screen sections.
- Referenced image paths in index: 258
- Actual files in deploy assets folder: 258
- Missing referenced assets: 0
- Non-JPEG/JPG asset files: 0

## Missing referenced assets

None

## Non-JPEG files

None

## Note

If images still fail in Google Sites, the cause is almost certainly deploy structure, not index mapping: `index.html` must be hosted beside the `assets/` folder on GitHub Pages. Google Sites embed-code blocks cannot host the relative `assets/...` folder.
