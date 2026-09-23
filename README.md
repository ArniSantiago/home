# Arni Santiago — complete GitHub Pages package

This package contains the two standalone sites, all downloaded image/PDF assets, GitHub Pages project-route fixes, the portfolio lightbox chunk, and an accessibility stylesheet for the design site.

## Repository root

- `index.html` — landing page
- `arni-design/` — design website
- `arni-portfolio/` — email portfolio
- `.nojekyll` — static hosting marker

## URLs

- https://arnisantiago.github.io/home/
- https://arnisantiago.github.io/home/arni-design/
- https://arnisantiago.github.io/home/arni-portfolio/

## Revisions in this package

- `arni-portfolio/assets/Lightbox-B8iNrwqT.js` fixes the dynamically imported lightbox error.
- `arni-design/assets/accessibility-16px.css` sets a 16px minimum for body text, labels, captions, metadata, helper text, small text, and notifications while leaving larger headings larger.
- `arni-design/index.html` links that stylesheet.

## Push with GitHub Desktop

Clone `ArniSantiago/home`, preserve the hidden `.git` folder, replace the repository contents with this package contents, commit to `main`, and push origin. Configure Pages as **Deploy from a branch → main → /(root)**.
