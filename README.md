# Next Next Next... Finished — Jekyll edition

Jekyll-ready migration of the existing blog. The repository includes the complete Markdown post archive, images, layouts, pagination, an RSS feed, SEO metadata, a sitemap, and a GitHub Pages deployment workflow.

## Preview locally

Install Ruby 3.3 and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/nextnextnextfinishedblog-jekyll/>.

## Publish

1. Create a GitHub repository named `nextnextnextfinishedblog-jekyll`.
2. Push this repository's `main` branch.
3. In **Settings → Pages**, choose **GitHub Actions** as the source.

If the repository name or owner changes, update `url` and `baseurl` in `_config.yml`.

## Add a post

Create `_posts/YYYY-MM-DD-your-post-title.md` with YAML front matter:

```yaml
---
title: "Post title"
date: 2026-07-21
tags:
  - example
---
```

