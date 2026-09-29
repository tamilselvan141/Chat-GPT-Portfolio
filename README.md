# Tamilselvan — Product Designer

Static export of the portfolio website built with ChatGPT Sites. It includes the published pages, JavaScript and CSS bundles, fonts/icons, and the project imagery.

## Run locally

From the repository root, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open <http://localhost:8000>. No package installation or build step is required; runtime libraries are included in the JavaScript bundles.

## Project structure

- `dist/index.html` — home page
- `dist/contact/`, `dist/passion/`, `dist/design/` — additional pages and case studies
- `dist/assets/` — bundled JavaScript, CSS, and portfolio images
- `dist/favicon*` — site icons

The Sites source repository exposed only the production static export, not the original component files or a package manifest. The JavaScript bundles are executable but are not the original editable React source. Image assets in this GitHub copy were encoded as WebP to keep the complete project practical to transfer; references in the export were updated accordingly. The original published Site remains unchanged.

## Deployment

Serve `dist/` as a static website. Configure the host to retain the included nested `index.html` files for direct case study URLs.
