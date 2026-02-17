# Kai Lynn Wong - CV & Research Blog

Personal website built with [Quarto](https://quarto.org/) featuring my CV and research blog.

**Live Site:** https://lynnotto.github.io/potstickers-

## About

This site serves as both my professional CV and a platform for sharing thoughts on research, coding, and bioinformatics. The site is built with Quarto and automatically deployed to GitHub Pages via GitHub Actions.

## Local Development

1. Install Quarto: https://quarto.org/docs/get-started/
2. Clone this repository
3. Run `quarto preview` to start local server
4. Visit http://localhost:4200

## Adding Blog Posts

1. Create new directory: `posts/YYYY-MM-post-title/`
2. Create `index.qmd` in that directory
3. Add YAML front matter with title, date, description, categories
4. Write content in Markdown
5. Commit and push to main branch
6. GitHub Actions will automatically deploy

Example front matter:

```yaml
---
title: "Your Post Title"
description: "A brief description of your post"
author: "Kai Lynn Wong"
date: "2026-02-17"
categories: [category1, category2]
draft: false
---
```

## Technology Stack

- [Quarto](https://quarto.org/) - Static site generator for scientific and technical publishing
- [GitHub Pages](https://pages.github.com/) - Free hosting for static sites
- [GitHub Actions](https://github.com/features/actions) - CI/CD for automatic deployment

## Structure

```
/
├── _quarto.yml              # Main site configuration
├── index.qmd                # CV homepage
├── blog.qmd                 # Blog listing page
├── posts/                   # All blog posts
│   └── _metadata.yml        # Default settings for posts
└── .github/
    └── workflows/
        └── publish.yml      # Deployment workflow
```

## License

Content is © Kai Lynn Wong. Code is open source and available under the MIT license.
