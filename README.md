# The Long Goodbye — V5.7.10 Full JP Deploy Build

This package merges the full uploaded JPEG-only asset folder with the corrected bilingual/Japanese index.

## Use

Upload the contents of this ZIP so that:

- `index.html` is at the site root.
- the complete `assets/` folder sits beside it.
- do not rename asset files unless you also update `index.html`.

## Included

- Full base asset folder from `tlg_v5_6_24_JPEG_ONLY_ASSETS_FOLDER.zip`
- Updated Japanese/English index with translated route text and translated endings
- Japanese menu assets:
  - `assets/menu_locked_secret_jp.jpg` with `隠しルート`
  - `assets/menu_unlocked_kenji_jp.jpg`
- Expanded Marcus assets
- Harrison bittersweet and bad ending assets, mapped to the Japanese and English ending logic
- Patch and audit manifests

## Current audit summary

- Referenced image assets in index: 258
- Image files included in asset folder: 436
- JPEG/JPG image files included: 436
- Non-JPEG image files included: 0
- Missing referenced assets: 0
- Extra/unreferenced image assets preserved from base folder: 178

## Notes

This is a full deploy package, not a small patch bundle.
