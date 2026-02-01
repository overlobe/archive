# AGENTS.md

## Project Overview

**archive** is a Jekyll-based website hosting an archive of text works. Uses the Hitchens theme (a typography-focused Jekyll theme). Deployed via GitHub Pages.

## Architecture & Structure

```
├── _config.yml          # Jekyll configuration
├── _data/               # Data files
├── _includes/           # Reusable HTML partials
├── Gemfile              # Ruby dependencies
├── CODE_OF_CONDUCT.md   # Community guidelines
└── README.md            # Theme documentation
```

This is a standard Jekyll site using the Hitchens theme.

## Setup & Commands

```bash
# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

**Deployment:** GitHub Pages — push to main branch auto-deploys.

## Code Style & Conventions

- Jekyll/Liquid templating
- Markdown for content
- Hitchens theme conventions for layout and styling
- Content goes in appropriate Jekyll collections or posts

## What NOT to Do

- Don't modify the core Hitchens theme files without good reason
- Don't break GitHub Pages compatibility
