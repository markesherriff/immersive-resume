# Immersive Resume

A single-page, scrollytelling, 8-bit/16-bit skateboarding-themed resume/portfolio for Mark Sherriff.

Everything (HTML, CSS, and JS) lives in `index.html` — a self-contained static page with no build step and no external runtime dependency beyond a Google Fonts stylesheet. The résumé PDF lives in `assets/`.

## Running locally

Just open `index.html` in a browser, or serve the folder locally, e.g.:

```
npx serve .
```

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo's **Settings → Pages**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. GitHub publishes it at `https://<username>.github.io/<repo-name>/` within a minute or two of each push.

## Updating the résumé PDF

Replace `assets/mark-sherriff-resume.pdf` with a new export of the same file name, or update the `href`s in `index.html` if you rename it.
