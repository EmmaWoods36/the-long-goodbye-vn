# Clean JP Deploy Audit

This package removes unreferenced source-upload/reference files and keeps only assets used by `index.html`, plus documentation/manifest files.

## Counts

- Index image references: 258
- Referenced images included: 258
- Missing referenced images: 0
- Asset image files in clean package: 258
- Non-JPEG image files: 0
- `source_uploads_all__*` files included: 0
- Any image filename containing `source`: 0

## Notes

- The removed `source_uploads_all__*` images are not required for deployment unless you want to keep them as backups/reference art.
- The game only needs the assets referenced by `index.html`.
