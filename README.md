# ravi-ramchandran.github.io

This repository contains a simple Jekyll-based personal site for Ravi Ramchandran.

What I added to make this publishable as a GitHub Pages site:

- A GitHub Actions workflow at `.github/workflows/pages.yml` that builds the site with Bundler + Jekyll and deploys to GitHub Pages on pushes to `main`.
- A `Gemfile` that uses the `github-pages` gem so the CI build environment matches GitHub Pages.
- Updated `_config.yml` to set the `url` and `baseurl` values.

How to publish locally or preview:

1. Install Ruby (>= 2.7) and Bundler.
2. Run `bundle install` to install dependencies.
3. Run `bundle exec jekyll serve` to preview the site at <http://localhost:4000>.

Notes:
- This is a user site repository (named `username.github.io`) so GitHub Pages will serve content from the root of the `main` branch.
- The included workflow ensures the site is built and deployed automatically when you push to `main`.
