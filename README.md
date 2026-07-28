# CROWNLINGS — coming-soon site

Public marketing site for **CROWNLINGS**, kept in its own repo on purpose so the game's
source code (`jarkkitni/crownlings`, private) never has to be exposed to host this page.

Plain static HTML — no build step, no framework, no backend. `index.html` is
self-contained (inline CSS) and pulls a handful of curated art/video assets from
`assets/`.

## Hosting

Deployed via **GitHub Pages** straight off this repo:
1. Push this repo to `main` on GitHub.
2. Repo → Settings → Pages → Source: **Deploy from a branch** → Branch `main`, folder `/ (root)`.
3. Live at `https://jarkkitni.github.io/crownlings-site/`.

`.nojekyll` is included so GitHub Pages serves the files as-is (skips Jekyll processing).

## Updating

- Swap the Facebook link: search `TODO` in `index.html` (two spots — hero CTA + footer).
- Swap in the real Steam Wishlist link once the store page is approved: replace the
  disabled `.btn-primary` span in the hero with a real `<a>` pointing at the Steam page.
- Art source of truth lives in the game repo's `art/` folder — copy over any updated PNGs
  into `assets/img/` under the same filenames to keep this page in sync.
