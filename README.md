# arni-design

This folder is a standalone static copy recovered from:
https://arnidesign-kmipondm.manus.space/

## Folder layout

- `index.html` — site entry point
- `assets/` — JavaScript and CSS bundles
- `manus-storage/` — downloaded images, PDFs, and other site assets

## Local preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>. The site is client-rendered, so use a static host that serves `index.html` and the root-level folders as-is.

## Notes

This copy removes Manus editor and analytics scripts. It preserves the public portfolio content and downloaded assets. The contact form, if present, may still depend on its original external form endpoint.
