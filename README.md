# GitHub Pages route patch

Replace these two files in the existing `home` repository:

- `arni-design/assets/index-CN11aZuE.js`
- `arni-portfolio/assets/index-BupzelAX.js`

These bundles recognize the GitHub Pages project paths:

- `/home/arni-design/`
- `/home/arni-portfolio/`

The old bundles only recognized `/`, which caused the app itself to render its 404 page even though GitHub successfully served each `index.html`.
