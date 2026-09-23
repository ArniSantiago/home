# Arni Santiago — complete GitHub Pages package

This package is ready to push to the public GitHub repository named `home`. It contains:

- A root landing page at `index.html`
- The Arni Design website at `arni-design/index.html`
- The Email Design Portfolio at `arni-portfolio/index.html`
- All 19 Arni Design image/PDF assets
- All 21 Email Design Portfolio image assets
- `.nojekyll` for static hosting
- JavaScript route fixes for GitHub Pages project paths

## Expected URLs

- https://arnisantiago.github.io/home/
- https://arnisantiago.github.io/home/arni-design/
- https://arnisantiago.github.io/home/arni-portfolio/

## Push with GitHub Desktop

1. In GitHub Desktop, choose **File → Clone repository**.
2. Select `ArniSantiago/home` and clone it to your computer.
3. Open the cloned `home` folder in your file manager.
4. Delete the old files inside it, but do not delete the hidden `.git` folder.
5. Copy the contents of this package into the cloned `home` folder.
6. Return to GitHub Desktop.
7. Commit the changes to `main` with a message such as `Restore complete portfolio websites`.
8. Click **Push origin**.
9. In GitHub **Settings → Pages**, use **Deploy from a branch → main → /(root)**.

The repository root must directly contain `index.html`, `arni-design/`, and `arni-portfolio/`. Do not place this package inside another nested folder.
