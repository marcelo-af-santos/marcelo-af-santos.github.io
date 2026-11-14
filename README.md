# marcelo-af-santos.github.io

Personal academic website of Marcelo dos Santos, served by GitHub Pages at <https://marcelo-af-santos.github.io>.

Plain HTML and CSS, no build step:

- `index.html` — Home tab (about, links, contact)
- `research.html` — Research tab (publications)
- `style.css` — styling (light and dark themes), shared by all pages
- `cv.pdf` — CV; replace this file to update it (keep the name so the link stays stable)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

To add a paper, copy one of the `<li>` entries in the Publications list in `research.html`.

To add a tab, copy `research.html` to a new file, then add a link to it in the `<nav class="tabs">` block of every page. On each page, put `aria-current="page"` on the link to that page itself.
