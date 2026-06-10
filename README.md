# The Long Goodbye — JP Full Build V5.7.10

This package contains the updated `index.html` for the bilingual English/Japanese visual novel build.

## What is included

- Full English story script preserved in `DATA`
- Full Japanese story script added in `DATA_JA`
- Japanese ending titles and ending copy translated
- Ending assets mapped to the same English/Japanese ending logic
- Japanese locked/revealed menu assets included
- Marcus expanded assets included
- Harrison bittersweet and bad ending assets included as JPG files
- Full audit fixes applied

## Important files

- `index.html` — deploy this as the game page
- `ASSET_MANIFEST.md` — simplified asset/mapping manifest
- `ENDING_TRANSLATION_PATCH_REPORT.md` — Japanese ending translation patch notes
- `FULL_SCRIPT_AUDIT_REPORT.md` — full audit report
- `FULL_SCRIPT_AUDIT_REPORT_V3.md` — final audit confirmation
- `assets/ASSET_PATCH_MANIFEST.md` — Marcus + JP menu asset patch notes
- `assets/HARRISON_ENDING_ASSET_PATCH_MANIFEST.md` — Harrison ending art patch notes
- `assets/FULL_AUDIT_FIXES_MANIFEST.md` — audit cleanup notes

## Deploy note

Keep the `assets/` folder next to `index.html` when uploading to GitHub Pages or Google Sites embedding. The image paths in the HTML expect `assets/<filename>`.

## Final checks

- Uncapped scenes: 0
- Deploy image format: JPG/JPEG only
- Japanese ending assets: mapped to same ending keys as English
- Tommy `Back to You` and `Endless Loop`: unchanged per request
