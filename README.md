# Diogo F. Soares Academic Website

This repository contains the source for the personal academic website hosted at <https://dfmsoares.github.io>. The site is built with [Quarto](https://quarto.org/) and published as a static GitHub Pages site.

## Install Quarto

Install Quarto from the official download page:

<https://quarto.org/docs/get-started/>

After installation, confirm that it is available:

```sh
quarto --version
```

## Preview Locally

From the repository root, run:

```sh
quarto preview
```

Quarto will render the site and start a local preview server.

## Render the Site

To build the static site locally, run:

```sh
quarto render
```

Rendered files are written to `_site/`.

## Publish with GitHub Pages

The GitHub Actions workflow in `.github/workflows/static.yml` installs Quarto, renders the site, uploads `_site/`, and deploys it to GitHub Pages whenever changes are pushed to `main`.

Make sure GitHub Pages is configured to use GitHub Actions as the source in the repository settings.

