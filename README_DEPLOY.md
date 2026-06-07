# The Long Goodbye VN — Source Package

This package is the external-assets/mobile-friendly version of the HTML visual novel demo.

## Files

- `index.html` — the full game code: HTML, CSS, JavaScript, route logic, save logic, CG gallery, endings, and image maps.
- `assets/` — all image assets referenced by the game as relative paths.

## How images are referenced

Images are not embedded directly in this version. They are linked by relative paths like:

```js
src: 'assets/example_image.webp'
```

The main systems are:

- `ASSET_META` — maps each asset key to its title, route, and image file path.
- `GALLERY_ORDER` — determines which images appear in the CG gallery and their order.
- `SCENE_ASSETS` — assigns image keys to route scenes, so gameplay knows which CG/portrait to show.
- ending thumbnail mapping — assigns specific CGs to ending cards.

## How to test locally on desktop

Unzip the package, keep `index.html` next to the `assets` folder, then open `index.html` in Chrome or Edge.

If browser security blocks local files, serve it over a local web server:

```bash
cd /path/to/tlg-vn-source-package
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to test on iPhone

Opening local HTML/ZIP files on iPhone is unreliable because mobile browsers and file previews often block local JavaScript and/or relative asset loading.

Recommended options:

1. Host the folder as a static website on Netlify, GitHub Pages, or itch.io HTML game hosting.
2. Open the hosted HTTPS URL on iPhone.
3. Embed that hosted URL into Google Sites as an iframe/embed.

## Important

Do not upload only `index.html` by itself. The `assets` folder must be uploaded with it, in the same directory.
