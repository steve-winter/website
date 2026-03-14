# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages site hosted at stevewinter.io. It uses Jekyll with the Cayman theme and is deployed automatically by GitHub Pages on every push to the `master` branch.

## Architecture

- **`_config.yml`** — Jekyll configuration; currently sets the theme to `jekyll-theme-cayman`
- **`CNAME`** — Custom domain mapping to `stevewinter.io`
- **`README.md`** — Serves as the site's index page content (rendered by Jekyll)

## Local Development

```bash
# Install dependencies (requires Ruby and Bundler)
gem install bundler
bundle install

# Serve locally with live reload
bundle exec jekyll serve
```

The site will be available at http://localhost:4000.

## Deployment

Push to the `master` branch. GitHub Pages builds and deploys automatically.
