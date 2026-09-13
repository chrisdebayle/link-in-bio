# link-in-bio

Chris Debayle's "link in bio" page, hosted with GitHub Pages at
https://chrisdebayle.github.io/link-in-bio/

## Structure

- `index.html`, `styles.css`, `assets/` — the live site (plain HTML/CSS, no build step).
- `design/` — the editable source for this page in [Claude Design](https://claude.ai) canvas
  (`Link In Bio.dc.html` plus its runtime and design-system bundle). Not used by the live site;
  keep it around if you want to visually re-edit the layout later.

## Editing links

Open `index.html` and edit the `<a class="link" ...>` entries directly — each one is a plain
link with a `href`, label, and optional subtitle.

## Deploying

Pushing to `main` is enough — GitHub Pages serves straight from the repo root.
