# Portfolio

My graphic design work portfolio built with Jekyll.

## Getting Started

### Prerequisites
- Ruby 3.1 or higher
- Bundler (`gem install bundler`)

### Installation

1. Clone the repository
```bash
git clone https://github.com/kforshee15/Portfolio.git
cd Portfolio
```

2. Install dependencies
```bash
bundle install
```

3. Run the local server
```bash
bundle exec jekyll serve
```

4. Open your browser to `http://localhost:4000`

## Structure

- `_portfolio/` - Portfolio item files
- `_includes/` - Reusable HTML snippets
- `_layouts/` - Page templates
- `assets/` - CSS, JavaScript, and images
- `index.md` - Homepage

## Adding Portfolio Items

Create a new file in `_portfolio/` with front matter:

```yaml
---
layout: portfolio_item
title: Project Title
date: 2026-06-16
image: /assets/images/project.jpg
---

Project description here...
```

## Deployment

This site is ready to deploy to GitHub Pages. Push to the `main` branch and enable GitHub Pages in the repository settings.

Live website available at:
[Website](https://bettencourt.studio)