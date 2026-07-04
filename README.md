# Anyan Qi Website

This repository powers the personal academic website at https://qi-anyan.github.io.

## Site Content

- Homepage content lives in `_pages/about.md`.
- Site-wide profile details, links, and metadata live in `_config.yml`.
- Header navigation lives in `_data/navigation.yml`.
- Static images and favicons live in `images/`.

The site currently uses the homepage as the primary content surface, with sections for research, teaching, service, and honors.

## Local Build

Install the Ruby dependencies once:

```bash
bundle install
```

Build the site:

```bash
bundle exec jekyll build
```

Preview locally:

```bash
bundle exec jekyll serve -l -H localhost
```

GitHub Pages rebuilds the site after changes are merged to the publishing branch.
