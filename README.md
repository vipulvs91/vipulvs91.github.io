# Vipul V Suresh: portfolio

Source for my portfolio site, served by GitHub Pages at **https://vipulvs91.github.io/**.

It's a static HTML site (no build step) based on the *Future Imperfect* template by
[HTML5 UP](https://html5up.net), used under the Creative Commons Attribution 3.0 license (see `LICENSE.txt`).

## Layout

| Path | What it is |
|---|---|
| `index.html` | The whole site: project cards and the sidebar |
| `Vipul-Suresh-Resume.pdf` | Resume linked from the nav bar |
| `images/` | Project images (lowercase, no spaces) |
| `assets/css/main.css` | Compiled styles (edit `assets/sass/` and recompile, or edit this directly) |
| `svip.github.io/` | Redirect from the old address (vipulvs91.github.io/svip.github.io/) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are, without Jekyll |

## Updating

1. Create a branch: `git switch -c update-xyz`
2. Edit, then preview locally by opening `index.html` in a browser.
3. Commit, push, and open a pull request: `gh pr create --fill`
4. Merge the pull request. GitHub Pages redeploys `main` in about a minute.
