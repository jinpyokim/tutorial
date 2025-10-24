# Malleable Software — Minimal Astro Site

A single-page landing site with a black background and small white text.

## Quickstart

```bash
# 1) scaffold
mkdir malleable-software-site && cd $_

# 2) extract the ZIP you downloaded here

# 3) install & run
npm install
npm run dev
```

Then open the printed local URL.

## Build & deploy

```bash
npm run build
npm run preview
```

You can deploy the `./dist` folder to any static host (Cloudflare Pages, Netlify, Vercel, GitHub Pages).

## Customize
- Change the page title or description in `src/pages/index.astro`.
- Replace `public/favicon.svg` with your own logo.
- To keep the minimalist look, styles are inlined. If you prefer external CSS, we can split them into `src/styles/global.css`.
