# web-platform-dx.github.io

The [W3C WebDX Community Group](https://www.w3.org/community/webdx/) website, built with [Eleventy](https://www.11ty.dev/).

**Live site:** https://web-platform-dx.github.io

## Local development

Requires Node.js 18+.

```bash
npm install
npm run dev
```

This starts a local server with live reload.

To produce a production build:

```bash
npm run build
```

The output is written to `_site/`.

## Deployment

Pushes to `main` automatically build and deploy the site to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.
