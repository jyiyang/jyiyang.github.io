# Jack Yi Yang - Personal Website

A Jekyll-based personal website hosted on GitHub Pages.

## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) (2.5 or higher)
- [Bundler](https://bundler.io/)

## Setup

Install dependencies:

```bash
bundle install
```

## Build

Build the static site:

```bash
bundle exec jekyll build
```

The site will be generated in the `_site` directory.

## Serve Locally

Run a local development server:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

For live reload during development:

```bash
bundle exec jekyll serve --livereload
```

## Update Dependencies

Update all gems to their latest versions:

```bash
bundle update
```

Update a specific gem:

```bash
bundle update <gem-name>
```

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `master` branch.

## Project Structure

- `index.html` - Main page layout
- `_config.yml` - Jekyll configuration
- `assets/css/` - Stylesheets
- `_includes/` - Reusable content (about.md, publications.md)
- `assets/pdf/` - Resume and documents
