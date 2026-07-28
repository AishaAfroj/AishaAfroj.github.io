# Aisha Afroj - Personal Portfolio

A custom Hugo portfolio for Aisha Afroj, designed for GitHub Pages.

## Local preview

Install Hugo Extended 0.164.0 or newer, then run:

```sh
hugo server
```

## Production build

```sh
hugo --gc --minify
```

The GitHub Actions workflow publishes the site automatically after each push to `main`.

## Content updates

- Edit professional details in `data/portfolio.yaml`.
- Edit page titles and descriptions in `content/`.
- Replace `assets/images/aisha-profile.png` to update the portrait.
- Replace `static/files/aisha-afroj-cv.pdf` to update the downloadable CV.
