# PDF Toolkit

A minimal, client-side PDF toolkit for unlocking annotation/editing restrictions and merging PDFs.

## Features

- **Unlock** — strips owner-password permission flags from PDFs that open normally but block editing/annotating/copying
- **Merge** — combine multiple PDFs into one; drag to reorder before merging

## Deploy to GitHub Pages

1. Push this repo to GitHub (only `index.html` is needed)
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Save — your site will be live at `https://<username>.github.io/<repo>/`

## Privacy

Nothing is uploaded anywhere. All PDF processing runs entirely in your browser using [pdf-lib](https://pdf-lib.js.org/). Your files never leave your device.
